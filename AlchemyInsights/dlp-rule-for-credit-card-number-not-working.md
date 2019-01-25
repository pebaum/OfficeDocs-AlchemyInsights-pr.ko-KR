---
title: 작동 하지 않는 신용 카드 번호에 대 한 DLP 규칙
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478719"
---
<span data-ttu-id="6f06b-p101">**데이터 손실 방지 (DLP)** DLP 중요 한 정보 유형 o 365에서 사용 하는 경우에 **신용 카드 번호** 를 포함 하는 콘텐츠에 대 한 작동 하지 않음에 문제가 있을? 그렇다면 콘텐츠 트리거 하는데 필요한 정보를 포함 되어있는지 확인은 계산 하는 경우 DLP 정책입니다. 등 **신용 카드 정책** 85%의 신뢰도 사용 하 여 구성에 대 한 다음 계산 되 및 트리거 규칙에 대 한 검색 해야:</span><span class="sxs-lookup"><span data-stu-id="6f06b-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated. For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="6f06b-105">**[형식:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식을 지정할 수는 16 자리 또는 서식이 지정 되지 않은 (dddddddddddddddd) Luhn 테스트로 전달 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span> 
    
- <span data-ttu-id="6f06b-106">**[패턴:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** 모든 주요 브랜드 Visa, Mastercard, 검색 카드, JCB, American Express, gift 카드 및 diner 카드를 포함 하 여 전세계에서 카드를 감지 하는 매우 복잡 하 고 강력한 패턴입니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-106">**[Pattern:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span> 
    
- <span data-ttu-id="6f06b-107">**[체크섬:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬</span><span class="sxs-lookup"><span data-stu-id="6f06b-107">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span> 
    
- <span data-ttu-id="6f06b-108">**[정의:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 85%에 근접 300 자 내에 있는 경우,:</span><span class="sxs-lookup"><span data-stu-id="6f06b-108">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="6f06b-109">Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-109">The function Func_credit_card finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="6f06b-110">다음 중 하나가 충족됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-110">One of the following is true:</span></span> 
    
  - <span data-ttu-id="6f06b-111">Keyword_cc_verification의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-111">A keyword from Keyword_cc_verification is found.</span></span>
    
  - <span data-ttu-id="6f06b-112">Keyword_cc_name의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-112">A keyword from Keyword_cc_name is found</span></span>
    
  - <span data-ttu-id="6f06b-113">Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-113">The function Func_expiration_date finds a date in the right date format.</span></span>
    
  - <span data-ttu-id="6f06b-114">체크섬이 통과됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f06b-114">The checksum passes</span></span>
    
    <span data-ttu-id="6f06b-115">예, 다음 샘플 DLP 신용 카드 번호 정책에 대 한 트리거할:</span><span class="sxs-lookup"><span data-stu-id="6f06b-115">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>
    
  - <span data-ttu-id="6f06b-116">Visa: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="6f06b-116">Visa: 4485 3647 3952 7352</span></span> 
    
  - <span data-ttu-id="6f06b-117">2/2009 만료 됨:</span><span class="sxs-lookup"><span data-stu-id="6f06b-117">Expires: 2/2009</span></span>
    
<span data-ttu-id="6f06b-118">콘텐츠에 대 한 검색 되도록 하려면 **신용 카드 번호** 에 대해 필요한 것에 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하십시오.: [어떤 중요 한 정보 유형 찾도록 신용 카드 #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="6f06b-118">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="6f06b-119">다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="6f06b-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

