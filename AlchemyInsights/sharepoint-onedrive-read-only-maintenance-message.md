---
title: SharePoint 또는 OneDrive를 사용 하려고 할 때 유지 관리 메시지에 대 한 읽기 전용
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: cc232fba6f502e2b6f282a8c1a1e29221e36b70d
ms.sourcegitcommit: a285c609319ade038461e090e14a701830031825
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/24/2019
ms.locfileid: "35840521"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="1375b-102">SharePoint 또는 OneDrive를 사용 하려고 할 때 유지 관리 메시지에 대 한 읽기 전용</span><span class="sxs-lookup"><span data-stu-id="1375b-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="1375b-103">사용자는 SharePoint 또는 OneDrive를 사용 하려고 할 때 **유지 관리 메시지에 대 한 읽기 전용** 을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive.</span></span>  <span data-ttu-id="1375b-104">이 경우 [메시지 센터로](https://portal.office.com/adminportal/home#/MessageCenter)이동 하 여 테 넌 트에서 활성 유지 관리가 진행 되 고 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-104">If so, check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span> <span data-ttu-id="1375b-105">또한 [서비스 상태](https://portal.office.com/adminportal/home#/servicehealth) 대시보드를 확인 하 여 발생할 수 있는 모든 권고/인시던트가 있는지 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-105">Also, make sure to check the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) dashboard to check for any advisories/incidents that may be occurring.</span></span>

<span data-ttu-id="1375b-106">메시지 센터 또는 서비스 상태 대시보드가 테 넌 트에 대 한 현재 유지 관리에 대해 언급 하지 않은 경우이는 브라우저 캐싱 문제일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-106">If neither the Message Center or Service Health dashboard have noted anything about current maintenance for your tenant, this may be a browser caching issue.</span></span>

<span data-ttu-id="1375b-107">사이트를 탐색 하기 전에 브라우저 캐시를 지워야 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-107">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="1375b-108">Microsoft Edge 브라우저에서 **설정을**선택한 다음 **개인 정보 및 보안**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-108">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="1375b-109">**검색 지우기**에서 **지우려는 작업**선택을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-109">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="1375b-110">**쿠키 및 저장 된 웹 사이트 데이터**를 선택 하 고 **지우기를**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-110">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="1375b-111">Mozilla Firefox 또는 Google Chrome과 같은 다른 브라우저를 사용 하는 경우에는 이러한 단계가 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-111">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="1375b-112">또 다른 옵션으로는 SharePoint 사이트 또는 OneDrive를 새 InPrivate 창에서 열 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1375b-112">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>