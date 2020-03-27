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
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 2aca55ac2fefbb2035140a759a77730dc905a4e9
ms.sourcegitcommit: 926e4ab6aa64ddc7a244de633421eb2b817541f2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/26/2020
ms.locfileid: "42958740"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="cf2c0-102">SharePoint Online 제한</span><span class="sxs-lookup"><span data-stu-id="cf2c0-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="cf2c0-103">**중요**:이 새로운 시간 동안 sharepoint Online 및 OneDrive 서비스가 고가용성 상태를 유지 하도록 하기 위한 단계를 수행 하 고 있습니다. 자세한 내용은 [Sharepoint Online 임시 기능 조정을](https://aka.ms/ODSPAdjustments) 방문 하세요.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="cf2c0-104">**503 서버 사용 중 오류**</span><span class="sxs-lookup"><span data-stu-id="cf2c0-104">**503 server is busy error**</span></span>

<span data-ttu-id="cf2c0-105">SharePoint 또는 OneDrive 사이트로 이동 하려고 하면 사용자에 게 503 서버가 통화 중 이라는 오류가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-105">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="cf2c0-106">이 오류는 SharePoint 서비스 내의 제한으로 인해 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-106">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="cf2c0-107">SharePoint Online에서는 제한 기능을 사용 하 여 SharePoint Online 서비스의 최적의 성능과 안정성을 유지 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-107">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="cf2c0-108">제한은 리소스를 과도 하 게 사용 하지 못하도록 사용자 작업 수 또는 스크립트 또는 코드에의 한 동시 통화를 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-108">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="cf2c0-109">제한에 대 한 자세한 내용은 [SharePoint Online에서 제한 또는 차단 되지 않도록](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)합니다 .를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-109">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="cf2c0-110">이 오류가 제한과 관련이 없는 것으로 생각 되는 경우 [메시지 센터로](https://portal.office.com/adminportal/home#/MessageCenter)이동 하 여 테 넌 트에서 활성 유지 관리가 진행 되 고 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-110">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="cf2c0-111">마지막으로 [서비스 상태](https://portal.office.com/adminportal/home#/servicehealth) 페이지를 방문 하 여 발생할 수 있는 권고/인시던트가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="cf2c0-111">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

