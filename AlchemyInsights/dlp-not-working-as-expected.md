---
title: DLP가 예상 대로 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 3d8316502b4e51a101197a908cf691f0ab7f845a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35389619"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="296f9-102">DLP가 예상 대로 작동 하지 않음</span><span class="sxs-lookup"><span data-stu-id="296f9-102">DLP not working as expected</span></span>

<span data-ttu-id="296f9-103">Office 365에서 **DLP (데이터 손실 방지)** 에 대 한 문제가 예상 대로 작동 하지 않습니까?</span><span class="sxs-lookup"><span data-stu-id="296f9-103">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="296f9-104">이 경우 **dlp 정책이** 올바르게 설정 되어 있고 데이터에 **dlp 정책이** 평가 되는 동안 검색 하는 작업이 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="296f9-104">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
 <span data-ttu-id="296f9-105">**DLP 설정:**</span><span class="sxs-lookup"><span data-stu-id="296f9-105">**Setting up DLP:**</span></span>
  
<span data-ttu-id="296f9-106">DLP 정책을 사용 하면 조직의 중요 한 정보를 식별 하 고 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="296f9-106">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="296f9-107">DLP 정책을 설정 하려면 [여기](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)에서 정보를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="296f9-107">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="296f9-108">**DLP 정책에서 찾는 사항:**</span><span class="sxs-lookup"><span data-stu-id="296f9-108">**What DLP policies look for:**</span></span>
  
<span data-ttu-id="296f9-109">Office 365 보안 및 준수 센터에서 **기본 제공 중요 한 정보 유형을** 사용 하는 경우 DLP 정책은 이러한 중요 한 유형을 검색할 때 특정 패턴 및 요소를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="296f9-109">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="296f9-110">**기본 제공 중요 한 정보 유형:**</span><span class="sxs-lookup"><span data-stu-id="296f9-110">**Built-in Sensitive Information Types:**</span></span>

    <span data-ttu-id="296f9-111">기본 제공 중요 한 유형과 중요 한 유형을 검색할 때 DLP 정책에서 찾는 사항에 대 한 자세한 내용은 [중요 한 정보 유형에서 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="296f9-111">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="296f9-112">**사용자 지정 중요 한 정보 유형:**</span><span class="sxs-lookup"><span data-stu-id="296f9-112">**Custom Sensitive Information Types:**</span></span>

    <span data-ttu-id="296f9-113">사용자 지정 중요 한 정보 유형을 만들려는 경우에는 사용자 지정 중요 한 [정보](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)유형을 만드는 방법에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="296f9-113">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

 <span data-ttu-id="296f9-114">**보고서**</span><span class="sxs-lookup"><span data-stu-id="296f9-114">**Reports:**</span></span>
  
- <span data-ttu-id="296f9-115">DLP 보고서를 사용 하 여 중요 한 데이터를 파악 [합니다.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="296f9-115">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="296f9-116">이벤트에 대 한 구체적인 세부 정보를 [문제 보고서](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)와 함께 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="296f9-116">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
