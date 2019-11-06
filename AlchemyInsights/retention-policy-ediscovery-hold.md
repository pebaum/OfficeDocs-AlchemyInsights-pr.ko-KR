---
title: 2609-보존-또는-ediscovery-보류
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994076"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a><span data-ttu-id="62d0a-102">SharePoint Online 또는 비즈니스용 OneDrive에서 항목을 삭제할 수 없음</span><span class="sxs-lookup"><span data-stu-id="62d0a-102">Unable to delete items in SharePoint Online or OneDrive for Business</span></span>

<span data-ttu-id="62d0a-103">보존 정책, 보존 레이블 또는 eDiscovery 보류가 OneDrive 사이트의 SharePoint 또는 특정 항목에 적용 되므로 SharePoint Online 또는 비즈니스용 OneDrive에서 항목을 삭제 하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="62d0a-103">You or your users may be unable to delete items in SharePoint Online or OneDrive for Business because a retention policy, retention label, or eDiscovery hold is applied to a SharePoint of OneDrive site or to a specific item.</span></span> <span data-ttu-id="62d0a-104">여기에는 문서, 문서 버전, 폴더, 문서 라이브러리, 목록, 사이트 또는 사이트 모음을 삭제할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="62d0a-104">This includes being unable to delete a document, a document version, a folder, a document library, a list, an app, a site, or a site collection.</span></span> <span data-ttu-id="62d0a-105">다음은 보존 되는 항목을 삭제 하려고 할 때 발생할 수 있는 오류 메시지의 몇 가지 예입니다.</span><span class="sxs-lookup"><span data-stu-id="62d0a-105">Here are some examples of the error messages you may received if you try to delete an item that is being retained:</span></span>

- <span data-ttu-id="62d0a-106">"이 사이트는 eDiscovery 보류 또는 보존 정책에 포함 되어 있으므로 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-106">"This site cannot be deleted because it is included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="62d0a-107">"이 사이트에는 삭제를 차단 하도록 설정 된 준수 정책이 있습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-107">"This site has a compliance policy set to block deletion"</span></span>
- <span data-ttu-id="62d0a-108">"준수 정책이 현재이 사이트 삭제를 차단 하 고 있습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-108">"A compliance policy is currently blocking this site deletion"</span></span>
- <span data-ttu-id="62d0a-109">"이 사이트 모음은 eDiscovery 보류 또는 보존 정책에 포함 된 사이트를 포함 하므로 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-109">"This site collection can’t be deleted because it contains sites that are included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="62d0a-110">"폴더를 삭제 하기 전에이 폴더의 모든 항목을 삭제 해야 합니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-110">"You have to delete all the items in this folder before you delete the folder"</span></span>
- <span data-ttu-id="62d0a-111">"이 항목의 버전은 보류 중이거나 보존 정책 이므로 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-111">"Versions of this item cannot be deleted because it is on hold or retention policy"</span></span>
- <span data-ttu-id="62d0a-112">"보류 중인 항목은 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-112">"Item cannot be deleted while on hold"</span></span>
- <span data-ttu-id="62d0a-113">"이 항목에 적용 된 레이블로 인해 편집 하거나 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-113">"The label that's applied to this item prevents it from being edited or deleted"</span></span>
- <span data-ttu-id="62d0a-114">"보류 또는 보존 정책을 설정 하는 동안 목록을 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-114">"List cannot be deleted while on hold or retention policy"</span></span>
- <span data-ttu-id="62d0a-115">"목록이 차단 되거나 보존 정책이 적용 되는 경우에는 삭제할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="62d0a-115">"The list cannot be deleted if it is blocked or if a retention policy is applied to it"</span></span>

<span data-ttu-id="62d0a-116">이러한 시나리오 중 하나에서 항목을 삭제 하려면 보존 정책, 보존 레이블 또는 eDiscovery 보류를 제거 해야 합니다 (또는 보존 정책에서 사이트를 제외 해야 하는 경우).</span><span class="sxs-lookup"><span data-stu-id="62d0a-116">To delete items in one of these scenarios, the retention policy, retention label, or eDiscovery hold has to be removed (or a site has to be excluded from a retention policy).</span></span> <span data-ttu-id="62d0a-117">이 문제를 일으킨 해당 보존을 사용 하지 않도록 설정 하거나 제외 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="62d0a-117">You need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="62d0a-118">보존 정책이 제거 된 후에는 변경 내용이 적용 되는 데 최대 24 시간이 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="62d0a-118">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> 

<span data-ttu-id="62d0a-119">SharePoint 사이트 및 OneDrive 계정에 적용할 수 있는 여러 가지 보존 및 유지 기능에 대 한 자세한 내용은 다음 항목 중 하나를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="62d0a-119">For information about about the different retention and hold features that can be applied to SharePoint sites and OneDrive accounts, see one of the following topics.</span></span>

- [<span data-ttu-id="62d0a-120">보존 정책 개요</span><span class="sxs-lookup"><span data-stu-id="62d0a-120">Overview of retention policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [<span data-ttu-id="62d0a-121">보존 레이블 개요</span><span class="sxs-lookup"><span data-stu-id="62d0a-121">Overview of retention labels</span></span>](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [<span data-ttu-id="62d0a-122">Advanced eDiscovery에서 보류 관리</span><span class="sxs-lookup"><span data-stu-id="62d0a-122">Manage holds in Advanced eDiscovery</span></span>](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [<span data-ttu-id="62d0a-123">eDiscovery 보류</span><span class="sxs-lookup"><span data-stu-id="62d0a-123">eDiscovery holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [<span data-ttu-id="62d0a-124">레거시 사이트 폐쇄 및 삭제 정책</span><span class="sxs-lookup"><span data-stu-id="62d0a-124">Legacy site closure and deletion policies</span></span>](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
