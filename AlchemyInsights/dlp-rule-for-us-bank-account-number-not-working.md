---
title: US 은행 계좌 번호에 대 한 DLP 규칙이 작동 하지 않음
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 9ebfa6bc09cef9ab7c30bddb4fcb8b6be3ab55a5
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404275"
---
<span data-ttu-id="e856b-102">O365에서 dlp 중요 한 정보 유형을 사용할 때 **US 은행 계좌 번호가** 포함 된 콘텐츠에 대해 **dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="e856b-102">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="e856b-103">이 경우 콘텐츠를 평가할 때 필요한 DLP 정책에 대 한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-103">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="e856b-104">예를 들어 **미국 은행 계좌 번호** 정책의 신뢰 수준이 85%로 구성 된 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-104">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="e856b-105">**[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 자리 숫자</span><span class="sxs-lookup"><span data-stu-id="e856b-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span> 
    
- <span data-ttu-id="e856b-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 자리 연속 숫자입니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span> 
    
- <span data-ttu-id="e856b-107">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="e856b-108">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 75% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="e856b-109">Regex_usa_bank_account_number 정규식은 해당 패턴과 일치 하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-109">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>
    
  - <span data-ttu-id="e856b-110">Keyword_usa_Bank_Account의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-110">A keyword from Keyword_usa_Bank_Account is found.</span></span>
    
    <span data-ttu-id="e856b-111">예를 들어 다음은 **US 은행 계좌 번호** 정책 (계정 78344011 확인)을 트리거하는 예제입니다.</span><span class="sxs-lookup"><span data-stu-id="e856b-111">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span> 
    
<span data-ttu-id="e856b-112">콘텐츠에 대 한 **미국 은행 계좌 번호** 를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 US 은행 계좌 번호에 대해 어떻게 나타나는지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="e856b-112">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="e856b-113">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="e856b-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

