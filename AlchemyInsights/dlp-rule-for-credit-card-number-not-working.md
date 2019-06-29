---
title: 신용 카드 번호에 대 한 DLP 규칙이 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 5d3bdb3b074c485a2b19e934724ba6e74c84deae
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35389583"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="535e0-102">신용 카드 번호 관련 DLP 문제</span><span class="sxs-lookup"><span data-stu-id="535e0-102">DLP issues with Credit Card Numbers</span></span>

<span data-ttu-id="535e0-103">O365에서 DLP 중요 한 정보 유형을 사용할 때 **신용 카드 번호가** 포함 된 콘텐츠에 대해 **Dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="535e0-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="535e0-104">이 경우에는 콘텐츠를 평가할 때 DLP 정책을 트리거하는 데 필요한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-104">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="535e0-105">예를 들어 신뢰 수준이 85% 인 **신용 카드 정책의** 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-105">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="535e0-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식이 있거나 서식이 없을 수 있는 16 자리 숫자 (dddddddddddddddd)로, Luhn 테스트를 통과 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="535e0-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** MasterCard, 검색 카드, JCB, 미국 익스프레스, 선물 카드 및 식사 권을 카드를 포함 하 여 전 세계 모든 주요 브랜드에서 카드를 검색 하는 매우 복잡 하 고 강력한 패턴입니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="535e0-108">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬</span><span class="sxs-lookup"><span data-stu-id="535e0-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="535e0-109">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 85% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="535e0-110">Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-110">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="535e0-111">다음 중 하나가 충족됩니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-111">One of the following is true:</span></span>

  - <span data-ttu-id="535e0-112">Keyword_cc_verification의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-112">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="535e0-113">Keyword_cc_name에서 키워드가 발견 됨</span><span class="sxs-lookup"><span data-stu-id="535e0-113">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="535e0-114">Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-114">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="535e0-115">체크섬 통과</span><span class="sxs-lookup"><span data-stu-id="535e0-115">The checksum passes</span></span>

    <span data-ttu-id="535e0-116">예를 들어 다음은 DLP 신용 카드 번호 정책을 트리거하는 예제입니다.</span><span class="sxs-lookup"><span data-stu-id="535e0-116">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="535e0-117"><: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="535e0-117">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="535e0-118">만료 날짜: 2/2009</span><span class="sxs-lookup"><span data-stu-id="535e0-118">Expires: 2/2009</span></span>

<span data-ttu-id="535e0-119">콘텐츠의 **신용 카드 번호** 를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 신용 카드 #에 대해 어떤 모양 인지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number) 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="535e0-119">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="535e0-120">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="535e0-120">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  