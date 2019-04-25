---
title: 신용 카드 번호에 대 한 DLP 규칙이 작동 하지 않음
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e1d60c493a27efb7f724d57051e21fad5bd0242f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404512"
---
<span data-ttu-id="895b3-102">O365에서 dlp 중요 한 정보 유형을 사용할 때 **신용 카드 번호가** 포함 된 콘텐츠에 대해 **dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="895b3-102">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="895b3-103">이 경우에는 콘텐츠를 평가할 때 DLP 정책을 트리거하는 데 필요한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-103">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="895b3-104">예를 들어 신뢰 수준이 85% 인 **신용 카드 정책의** 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-104">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="895b3-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식이 있거나 서식이 없을 수 있는 16 자리 숫자 (dddddddddddddddd)로, Luhn 테스트를 통과 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span> 
    
- <span data-ttu-id="895b3-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** MasterCard, 검색 카드, jcb, 미국 익스프레스, 선물 카드 및 식사 권을 카드를 포함 하 여 전 세계 모든 주요 브랜드에서 카드를 검색 하는 매우 복잡 하 고 강력한 패턴입니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span> 
    
- <span data-ttu-id="895b3-107">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬</span><span class="sxs-lookup"><span data-stu-id="895b3-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span> 
    
- <span data-ttu-id="895b3-108">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 85% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="895b3-109">Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-109">The function Func_credit_card finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="895b3-110">다음 중 하나가 충족됩니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-110">One of the following is true:</span></span> 
    
  - <span data-ttu-id="895b3-111">Keyword_cc_verification의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-111">A keyword from Keyword_cc_verification is found.</span></span>
    
  - <span data-ttu-id="895b3-112">Keyword_cc_name에서 키워드가 발견 됨</span><span class="sxs-lookup"><span data-stu-id="895b3-112">A keyword from Keyword_cc_name is found</span></span>
    
  - <span data-ttu-id="895b3-113">Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-113">The function Func_expiration_date finds a date in the right date format.</span></span>
    
  - <span data-ttu-id="895b3-114">체크섬 통과</span><span class="sxs-lookup"><span data-stu-id="895b3-114">The checksum passes</span></span>
    
    <span data-ttu-id="895b3-115">예를 들어 다음은 DLP 신용 카드 번호 정책을 트리거하는 예제입니다.</span><span class="sxs-lookup"><span data-stu-id="895b3-115">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>
    
  - <span data-ttu-id="895b3-116"><: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="895b3-116">Visa: 4485 3647 3952 7352</span></span> 
    
  - <span data-ttu-id="895b3-117">만료 날짜: 2/2009</span><span class="sxs-lookup"><span data-stu-id="895b3-117">Expires: 2/2009</span></span>
    
<span data-ttu-id="895b3-118">콘텐츠의 **신용 카드 번호** 를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 신용 카드 #에 대해 어떤 모양 인지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number) 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="895b3-118">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="895b3-119">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="895b3-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

