---
title: SPMT를 사용한 SharePoint 마이그레이션
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2594"
ms.openlocfilehash: e7719d1fc6dda0d5bd340775219401dade2933fe
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931556"
---
# <a name="sharepoint-migration-with-spmt"></a><span data-ttu-id="bafcf-102">SPMT를 사용한 SharePoint 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="bafcf-102">SharePoint Migration with SPMT</span></span>

<span data-ttu-id="bafcf-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="bafcf-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="bafcf-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="bafcf-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="bafcf-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="bafcf-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="bafcf-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="bafcf-109">**SharePoint 마이그레이션 도구**</span><span class="sxs-lookup"><span data-stu-id="bafcf-109">**SharePoint Migration Tool**</span></span>

<span data-ttu-id="bafcf-110">가장 작은 파일 집합에서 대규모 엔터프라이즈 마이그레이션에 이르는 마이그레이션에 사용 하도록 설계 된 SharePoint 마이그레이션 도구를 통해 정보를 클라우드로 전송 하 고 최신 공동 작업 및 인텔리전스를 활용할 수 있습니다. Office 365 보안 솔루션</span><span class="sxs-lookup"><span data-stu-id="bafcf-110">Designed to be used for migrations ranging from the smallest set of files to a large scale enterprise migration, the SharePoint Migration Tool will allow you to transfer your information to the cloud and take advantage of the newest collaboration, intelligence, and security solutions with Office 365.</span></span>

- [<span data-ttu-id="bafcf-111">SharePoint 마이그레이션 도구 다운로드 및 설치</span><span class="sxs-lookup"><span data-stu-id="bafcf-111">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
- [<span data-ttu-id="bafcf-112">일반적인 SPMT 오류 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bafcf-112">Troubleshooting common SPMT issues and errors</span></span>](https://docs.microsoft.com/sharepointmigration/troubleshooting-common-spmt-issues)
- [<span data-ttu-id="bafcf-113">SPMT 설치 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bafcf-113">Troubleshooting SPMT installation issues</span></span>](https://docs.microsoft.com/sharepointmigration/spmt-install-issues#troubleshooting-spmt-installation-issues)
