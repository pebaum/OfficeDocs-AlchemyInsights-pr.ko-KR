---
title: 503 오류가 발생 한 SharePoint 마이그레이션 제한
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931664"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a><span data-ttu-id="7d8d4-102">503 오류가 발생 한 SharePoint 마이그레이션 제한</span><span class="sxs-lookup"><span data-stu-id="7d8d4-102">SharePoint migration throttling with 503 errors</span></span>

<span data-ttu-id="7d8d4-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="7d8d4-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="7d8d4-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="7d8d4-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="7d8d4-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="7d8d4-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="7d8d4-109">**SharePoint Online으로 마이그레이션할 때 503 오류 발생**</span><span class="sxs-lookup"><span data-stu-id="7d8d4-109">**503 errors when migrating to SharePoint Online**</span></span>

<span data-ttu-id="7d8d4-110">SharePoint Online으로 마이그레이션하고 503 오류를 수신 하는 것 처럼 보입니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-110">It appears you are migrating to SharePoint Online and receiving 503 errors.</span></span> <span data-ttu-id="7d8d4-111">가능한 한 빨리 도움이 될 수 있도록 아래 단계를 따르세요.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="7d8d4-112">**지원 센터**, **새 서비스 요청**을 차례로 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-112">Click **Contact Support**, and then **New Service Request**.</span></span>
2. <span data-ttu-id="7d8d4-113">제목 및 설명에 대해 503을 **사용 하 여 SharePoint 마이그레이션 제한을**입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-113">For the title and description, type **SharePoint Migration Throttling with 503**.</span></span>
3. <span data-ttu-id="7d8d4-114">티켓이 전송 된 후에는 다음 정보를 사용 하 여 업데이트 하세요.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-114">Once the ticket has been submitted, please update it with the following information:</span></span>
    - <span data-ttu-id="7d8d4-115">마이그레이션의 남은 양 (예: TBs 수)</span><span class="sxs-lookup"><span data-stu-id="7d8d4-115">How much left of migration (for example, how many TBs?).</span></span>
    - <span data-ttu-id="7d8d4-116">마이그레이션 시작 및 종료 날짜</span><span class="sxs-lookup"><span data-stu-id="7d8d4-116">Migration start and end date.</span></span>
    - <span data-ttu-id="7d8d4-117">콘텐츠를 마이그레이션하는 위치 (예: SharePoint Server, Box, GDrive, 파일 공유 등)에 대해 설명 합니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>
    - <span data-ttu-id="7d8d4-118">제한 오류 (예: 시간당 x 스로틀) 수를 예측 하 고 조정이 언제 수행 되는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="7d8d4-118">Estimate the number of throttling errors (for example, x throttle per hour?) and when did the throttling happen.</span></span>
    - <span data-ttu-id="7d8d4-119">사용 중인 마이그레이션 도구 (예: SPMT 또는 ShareGate)</span><span class="sxs-lookup"><span data-stu-id="7d8d4-119">Which migration tool you are using (for example, SPMT or ShareGate).</span></span>


