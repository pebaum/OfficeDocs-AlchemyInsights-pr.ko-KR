---
title: 일반 마이그레이션 성능 지침
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932484"
---
# <a name="general-migration-performance-guidance"></a><span data-ttu-id="3503b-102">일반 마이그레이션 성능 지침</span><span class="sxs-lookup"><span data-stu-id="3503b-102">General migration performance guidance</span></span>

<span data-ttu-id="3503b-103">**중요**: SharePoint Online 및 OneDrive 고객 다수는 백그라운드에서 실행되는 서비스를 상대로 업무상 중요한 응용 프로그램을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="3503b-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="3503b-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="3503b-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="3503b-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="3503b-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="3503b-109">**마이그레이션 성능 지침**</span><span class="sxs-lookup"><span data-stu-id="3503b-109">**Migration performance guidance**</span></span>

<span data-ttu-id="3503b-p103">이동 성능은 네트워크 기반 설비, 파일 크기, 이동 시간 및 쓰로틀링의 영향을 받을 수 있습니다. 이러한 점을 이해 시이동의 효율성을 계획하고 최대화하는데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="3503b-p103">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling. Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

- [<span data-ttu-id="3503b-112">일반 마이그레이션 성능 지침</span><span class="sxs-lookup"><span data-stu-id="3503b-112">General migration performance guidance</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)
