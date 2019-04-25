---
title: US/영국 여권 번호가 작동 하지 않는 DLP 규칙
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: bb80ef07364a575f6032bb105cff83cd8f95bd63
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404387"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="19636-102">DLP-US/영국 여권 번호 관련 문제</span><span class="sxs-lookup"><span data-stu-id="19636-102">Problems with DLP - US/UK Passport Numbers</span></span>

<span data-ttu-id="19636-103">O365에서 dlp 중요 한 정보 유형을 사용할 때 **US/영국 여권 번호가** 포함 된 콘텐츠에 대해 **dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="19636-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="19636-104">이 경우 콘텐츠를 평가할 때 필요한 DLP 정책에 대 한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="19636-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="19636-105">예를 들어 **미국/영국 여권 번호** 정책의 신뢰 수준이 75% 인 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="19636-105">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span> 
  
- <span data-ttu-id="19636-106">**[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 9 자리 숫자</span><span class="sxs-lookup"><span data-stu-id="19636-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span> 
    
- <span data-ttu-id="19636-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 9 자리 연속 숫자</span><span class="sxs-lookup"><span data-stu-id="19636-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span> 
    
- <span data-ttu-id="19636-108">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없습니다.</span><span class="sxs-lookup"><span data-stu-id="19636-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="19636-109">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 75% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="19636-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="19636-110">Func_usa_uk_passport 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="19636-110">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="19636-111">Keyword_passport의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="19636-111">A keyword from Keyword_passport is found.</span></span>
    
    <span data-ttu-id="19636-112">예를 들어 미국 여권 번호 123456789에 대 한 다음 샘플은 **US/영국 여권 번호** 정책에 대해 트리거됩니다.</span><span class="sxs-lookup"><span data-stu-id="19636-112">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span> 
    
<span data-ttu-id="19636-113">콘텐츠에 대 한 us/영국 여권 번호를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 US/uk passport 번호에 대해 어떻게 나타나는지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="19636-113">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="19636-114">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="19636-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

