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
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932628"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="aa7b9-102">DLP가 예상 대로 작동 하지 않음</span><span class="sxs-lookup"><span data-stu-id="aa7b9-102">DLP not working as expected</span></span>

<span data-ttu-id="aa7b9-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="aa7b9-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="aa7b9-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="aa7b9-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="aa7b9-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="aa7b9-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

 <span data-ttu-id="aa7b9-109">**DLP 설정**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-109">**Setting up DLP**</span></span>

<span data-ttu-id="aa7b9-110">Office 365에서 **DLP (데이터 손실 방지)** 에 대 한 문제가 예상 대로 작동 하지 않습니까?</span><span class="sxs-lookup"><span data-stu-id="aa7b9-110">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="aa7b9-111">이 경우 **dlp 정책이** 올바르게 설정 되어 있고 데이터에 **dlp 정책이** 평가 되는 동안 검색 하는 작업이 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-111">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="aa7b9-112">DLP 정책을 사용 하면 조직의 중요 한 정보를 식별 하 고 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-112">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="aa7b9-113">DLP 정책을 설정 하려면 [여기](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)에서 정보를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-113">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="aa7b9-114">**DLP 정책에서 찾는 사항**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-114">**What DLP policies look for**</span></span>
  
<span data-ttu-id="aa7b9-115">Office 365 보안 및 준수 센터에서 **기본 제공 중요 한 정보 유형을** 사용 하는 경우 DLP 정책은 이러한 중요 한 유형을 검색할 때 특정 패턴 및 요소를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-115">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="aa7b9-116">**기본 제공 중요 한 정보 유형**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-116">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="aa7b9-117">기본 제공 중요 한 유형과 중요 한 유형을 검색할 때 DLP 정책에서 찾는 사항에 대 한 자세한 내용은 [중요 한 정보 유형에서 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-117">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="aa7b9-118">**사용자 지정 중요 한 정보 유형**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-118">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="aa7b9-119">사용자 지정 중요 한 정보 유형을 만들려는 경우에는 사용자 지정 중요 한 [정보](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)유형을 만드는 방법에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-119">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="aa7b9-120">**DLP 정책 테스트**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-120">**Test a DLP policy**</span></span>

<span data-ttu-id="aa7b9-121">기본 제공 또는 사용자 지정 중요 한 정보 유형을 사용 하 여 데이터를 테스트 하려면 **분류** > **중요 정보 유형에**서 **테스트 유형** 옵션을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-121">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="aa7b9-122">자세한 내용은 [사용자 지정 중요 한 정보 유형 테스트](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-122">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="aa7b9-123">**보고서**</span><span class="sxs-lookup"><span data-stu-id="aa7b9-123">**Reports**</span></span>
  
- <span data-ttu-id="aa7b9-124">DLP 보고서를 사용 하 여 중요 한 데이터를 파악 [합니다.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="aa7b9-124">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="aa7b9-125">이벤트에 대 한 구체적인 세부 정보를 [문제 보고서](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)와 함께 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="aa7b9-125">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
