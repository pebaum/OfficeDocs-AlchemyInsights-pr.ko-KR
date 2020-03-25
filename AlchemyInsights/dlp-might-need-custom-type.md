---
title: DLP에 사용자 지정 형식이 필요할 수 있음
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932664"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="105f9-102">DLP에 사용자 지정 형식이 필요할 수 있음</span><span class="sxs-lookup"><span data-stu-id="105f9-102">DLP might need a custom type</span></span>

<span data-ttu-id="105f9-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="105f9-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="105f9-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="105f9-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="105f9-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="105f9-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="105f9-109">**DLP에는 사용자 지정 정보 유형이 필요할 수 있습니다.**</span><span class="sxs-lookup"><span data-stu-id="105f9-109">**DLP may require a custom information type**</span></span>

<span data-ttu-id="105f9-110">DLP (데이터 손실 방지) 정책을 사용 하 여 조직에서 중요 한 데이터를 식별 하 고 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-110">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="105f9-111">일부 시나리오에서는 조직의 데이터를 보호 하기 위해 **사용자 지정** 중요 한 정보 유형을 직접 만들어야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-111">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="105f9-112">예를 들어 조직에서 조직의 특정 형식으로 직원 Id 또는 기타 데이터를 식별 하 고 보호 해야 할 수 있습니다. 이 경우 자세한 내용은 다음 문서를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="105f9-112">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="105f9-113">**기본 제공 중요한 정보 유형 사용자 지정**</span><span class="sxs-lookup"><span data-stu-id="105f9-113">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="105f9-114">기본 제공 중요 한 정보 유형이 몇 가지 수단 만으로 요구 사항을 충족 하는 경우 [에는 기본 제공 중요 한 정보 유형을 사용자 지정할](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type)수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-114">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="105f9-115">예를 들어 키워드를 추가 또는 제거 하거나, 날짜나 주소와 같은 지원 증거를 추가 하거나 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-115">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="105f9-116">**사용자 지정 중요한 정보 유형 만들기**</span><span class="sxs-lookup"><span data-stu-id="105f9-116">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="105f9-117">그러나 서로 다른 유형의 중요 한 정보를 식별 하 고 보호 해야 하는 경우에는 보안 & 준수 센터의 UI에서 [사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-117">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="105f9-118">**보안 및 준수 센터 PowerShell에서 사용자 지정 중요한 정보 유형 만들기**</span><span class="sxs-lookup"><span data-stu-id="105f9-118">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="105f9-119">마지막으로 UI가 필요한 모든 옵션을 제공 하지 않는 경우 [보안 & 준수 센터 PowerShell에서 사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell)수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-119">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="105f9-120">XML 파일을 시작 하 여 사용 가능한 모든 옵션을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="105f9-120">By starting with an XML file, you can use every option available.</span></span>
