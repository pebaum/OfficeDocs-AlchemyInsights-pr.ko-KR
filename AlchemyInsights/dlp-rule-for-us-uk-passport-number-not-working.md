---
title: 미국에 대 한 DLP 규칙 / 작동 하지 않음 영국 여권 번호
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 5722f7b6c9a2f905fed2ef4164787e020260edf7
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29656429"
---
<span data-ttu-id="3a031-p101">경우에 문제가 있는 **데이터 손실 방지 (DLP)** 콘텐츠를 포함 하는 것에 대 한 작동 하지는 **미국 / 영국 여권 번호** DLP 중요 한 정보 유형 o 365에서 사용 하는 경우? 그럴 경우 다음을 확인 콘텐츠 포함 DLP 정책이 원하는 내용을 계산 하는 경우에 필요한 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="3a031-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="3a031-104">예: 프로그램 **미국 / 영국 여권 번호** 75%의 신뢰 수준으로 구성 된 정책, 계산 되 하 고 다음을 트리거하려면 규칙에 대 한 검색 해야 합니다</span><span class="sxs-lookup"><span data-stu-id="3a031-104">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span> 
  
- <span data-ttu-id="3a031-105">**[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 숫자 9 개</span><span class="sxs-lookup"><span data-stu-id="3a031-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span> 
    
- <span data-ttu-id="3a031-106">**[패턴:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 연속 되는 숫자 9 개</span><span class="sxs-lookup"><span data-stu-id="3a031-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span> 
    
- <span data-ttu-id="3a031-107">**[체크섬:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없으면</span><span class="sxs-lookup"><span data-stu-id="3a031-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="3a031-108">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 75%에 근접 300 자 내에 있는 경우,:</span><span class="sxs-lookup"><span data-stu-id="3a031-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="3a031-109">Func_usa_uk_passport 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="3a031-109">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="3a031-110">Keyword_passport의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="3a031-110">A keyword from Keyword_passport is found.</span></span>
    
    <span data-ttu-id="3a031-111">다음 예제에 대 한 트리거할 예는 **미국 / 영국 여권 번호** 정책: 123456789 미국 여권 번호</span><span class="sxs-lookup"><span data-stu-id="3a031-111">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span> 
    
<span data-ttu-id="3a031-112">미국에 대 한 필요한 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하는 대화 내용에 대 한 검색 되도록 하려면 영국 여권 번호 /: [미국에 대 한 정보를 어떤 중요 한 정보 유형 / 영국 여권 번호](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="3a031-112">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="3a031-113">다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="3a031-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

