---
title: SharePoint Online 제한
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 5fdbb315698a58145e5437b0a7b127ce0062a76f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048622"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="a88a1-102">SharePoint Online 제한</span><span class="sxs-lookup"><span data-stu-id="a88a1-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="a88a1-103">SharePoint 또는 OneDrive 사이트로 이동 하려고 하면 사용자에 게 503 서버가 통화 중 이라는 오류가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="a88a1-104">이 오류는 SharePoint 서비스 내의 제한으로 인해 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="a88a1-105">SharePoint Online에서는 제한 기능을 사용 하 여 SharePoint Online 서비스의 최적의 성능과 안정성을 유지 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="a88a1-106">제한은 리소스를 과도 하 게 사용 하지 못하도록 사용자 작업 수 또는 스크립트 또는 코드에의 한 동시 통화를 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="a88a1-107">제한 된 시간이 되 면 사용자 지정 코드로 인해 발생 한 99%가 됩니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-107">If you do get throttled, 99% of the time it is because of custom code.</span></span>

<span data-ttu-id="a88a1-108">제한에 대 한 자세한 내용은 [SharePoint Online에서 제한 또는 차단 되지 않도록](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)합니다 .를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="a88a1-108">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="a88a1-109">이 오류가 제한과 관련이 없는 것으로 생각 되는 경우 [메시지 센터로](https://portal.office.com/adminportal/home#/MessageCenter)이동 하 여 테 넌 트에서 활성 유지 관리가 진행 되 고 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-109">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="a88a1-110">마지막으로 [서비스 상태](https://portal.office.com/adminportal/home#/servicehealth) 페이지를 방문 하 여 발생할 수 있는 권고/인시던트가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a88a1-110">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

