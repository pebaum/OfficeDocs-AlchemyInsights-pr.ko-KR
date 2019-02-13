---
title: DLP 예상 대로 작동 하지 않음
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 1e5ff53d903a14064147621df0a883152c32eff5
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29919662"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="e9014-102">DLP 예상 대로 작동 하지 않음</span><span class="sxs-lookup"><span data-stu-id="e9014-102">DLP not working as expected</span></span>


<span data-ttu-id="e9014-p101">**데이터 손실 방지 (DLP)** 에 문제가 예상 대로 작동 하지 않음 Office 365에서 데 있습니까? 그렇다면 **DLP 정책** 에 따라이 제대로 설치 하 고 데이터 **DLP 정책** 을 포함 하는 찾고 계산 하는 경우에 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="e9014-p101">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected? If so, make sure that your **DLP policy** is setup correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span> 
  
 <span data-ttu-id="e9014-105">**DLP를 설정 합니다.**</span><span class="sxs-lookup"><span data-stu-id="e9014-105">**Setting up DLP:**</span></span>
  
<span data-ttu-id="e9014-p102">DLP 정책을 식별 하 고 조직에 중요 한 정보를 보호할 수 있습니다. DLP 정책 설치, 정보를 사용 하려면 [여기](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)합니다.</span><span class="sxs-lookup"><span data-stu-id="e9014-p102">DLP policies allows you to identify and protect sensitive information in your organization. To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="e9014-108">**DLP 정책 나타나는지 확인합니다.**</span><span class="sxs-lookup"><span data-stu-id="e9014-108">**What DLP policies look for:**</span></span>
  
<span data-ttu-id="e9014-109">Office 365 보안 및 규정 준수 센터의 **기본 제공 중요 한 정보 유형** 를 사용 하는 경우 이러한 중요 한 형식을 검색 하는 경우 특정 패턴 및 요소에 대 한 DLP 정책을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="e9014-109">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span> 
  
- <span data-ttu-id="e9014-110">**기본 제공 중요 한 정보 유형:**</span><span class="sxs-lookup"><span data-stu-id="e9014-110">**Built-in Sensitive Information Types:**</span></span>
    
    <span data-ttu-id="e9014-111">기본 제공 중요 한 형식 및 중요 한 형식을 검색 하는 경우의 DLP 정책을 찾아에 대 한 정보를 참조 하십시오.: [중요 한 정보 유형을 찾습니다](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="e9014-111">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>
    
- <span data-ttu-id="e9014-112">**사용자 지정 중요 한 정보 유형:**</span><span class="sxs-lookup"><span data-stu-id="e9014-112">**Custom Sensitive Information Types:**</span></span>
    
    <span data-ttu-id="e9014-113">중요 한 정보를 사용자 지정 형식을 만들 하려는 경우 다음 문서를 사용자 지정 중요 한 유형을 만드는 방법에 대 한 정보 사용: [사용자 지정 중요 한 정보 유형 만들기](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="e9014-113">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>
    
 <span data-ttu-id="e9014-114">**보고서:**</span><span class="sxs-lookup"><span data-stu-id="e9014-114">**Reports:**</span></span>
  
- <span data-ttu-id="e9014-115">와 중요 한 데이터 정보를 가져올 [DLP 보고서.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="e9014-115">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>
    
- <span data-ttu-id="e9014-116">[위해 문제 보고서](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)와 함께 이벤트의 특정 세부 정보를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="e9014-116">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
    

