---
title: SharePoint Online 제한
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 9af4f09d50992c04a1f3d5a164093049a3ec3517
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931448"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="bf640-102">SharePoint Online 제한</span><span class="sxs-lookup"><span data-stu-id="bf640-102">SharePoint Online throttling</span></span>

<span data-ttu-id="bf640-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="bf640-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="bf640-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="bf640-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="bf640-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="bf640-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="bf640-109">**SharePoint Online 제한**</span><span class="sxs-lookup"><span data-stu-id="bf640-109">**SharePoint Online throttling**</span></span>

<span data-ttu-id="bf640-110">SharePoint Online에서는 제한 기능을 사용 하 여 SharePoint Online 서비스의 최적의 성능과 안정성을 유지 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-110">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="bf640-111">제한은 리소스를 과도 하 게 사용 하지 못하도록 사용자 작업 수 또는 스크립트 또는 코드에의 한 동시 통화를 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="bf640-111">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="bf640-112">자세한 내용을 보려면 아래 링크를 방문 하세요.</span><span class="sxs-lookup"><span data-stu-id="bf640-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="bf640-113">SharePoint Online에서 제한 또는 차단되지 않도록 방지</span><span class="sxs-lookup"><span data-stu-id="bf640-113">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="bf640-114">데이터 마이그레이션 및 SPO 제한</span><span class="sxs-lookup"><span data-stu-id="bf640-114">Data Migration and SPO Throttling </span></span>](https://blogs.technet.microsoft.com/sposupport/2017/08/12/data-migration-and-spo-service-throttling/)

- [<span data-ttu-id="bf640-115">SharePoint Online 및 OneDrive 마이그레이션 속도</span><span class="sxs-lookup"><span data-stu-id="bf640-115">SharePoint Online and OneDrive Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

 - [<span data-ttu-id="bf640-116">지 수 백오프를 사용 하 여 SharePoint Online 제한 처리</span><span class="sxs-lookup"><span data-stu-id="bf640-116">Handle SharePoint Online throttling by using exponential back off</span></span>](https://docs.microsoft.com/sharepoint/dev/solution-guidance/handle-sharepoint-online-throttling-by-using-exponential-back-off)

- [<span data-ttu-id="bf640-117">용량 계획 및 부하 테스트 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="bf640-117">Capacity planning and load testing SharePoint Online</span></span>](https://docs.microsoft.com/office365/enterprise/capacity-planning-and-load-testing-sharepoint-online)

