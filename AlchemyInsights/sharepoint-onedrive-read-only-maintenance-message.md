---
title: 127 전자 메일에 액세스할 때 TenantAccessBlockedException 오류를 가져올 것인가?
ms.author: kirks
author: Techwriter40
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
ms.openlocfilehash: 5613138e7613deb264a7ab2c966f8b9c4a24763d
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736408"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="b2a6b-102">SharePoint 또는 OneDrive를 사용 하려고 할 때 유지 관리 메시지에 대 한 읽기 전용</span><span class="sxs-lookup"><span data-stu-id="b2a6b-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="b2a6b-103">사용자는 SharePoint 또는 OneDrive를 사용 하려고 할 때 유지 관리 메시지에 대 한 읽기 전용을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-103">Users may receive a Read-Only for Maintenance message when attempting to use SharePoint or OneDrive.</span></span>

<span data-ttu-id="b2a6b-104">[메시지 센터로](https://portal.office.com/adminportal/home#/MessageCenter)이동 하 여 테 넌 트에서 활성 유지 관리가 진행 되 고 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-104">Check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span> <span data-ttu-id="b2a6b-105">마지막으로[서비스 상태](https://portal.office.com/adminportal/home#/servicehealth) 페이지를 방문 하 여 발생할 수 있는 권고/인시던트가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-105">Finally, ensure you visit the[Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

<span data-ttu-id="b2a6b-106">메시지 센터 또는 서비스 상태 대시보드가 테 넌 트에 대 한 현재 유지 관리에 대해 언급 하지 않은 경우이는 브라우저 캐싱 문제일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-106">If neither the Message Center or Service Health Dashboard have noted anything about current maintenance for your tenant, this may be a browser caching issue.</span></span>

<span data-ttu-id="b2a6b-107">사이트를 탐색 하기 전에 브라우저 캐시를 지워야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-107">Please attempt to clear the browser cache before navigating to the site.</span></span>

- <span data-ttu-id="b2a6b-108">Microsoft Edge 브라우저에서 추가 설정으로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-108">In the Microsoft Edge browser, go to More  Settings</span></span>

- <span data-ttu-id="b2a6b-109">검색 지우기에서 지우려는 작업 선택을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-109">Under Clear browsing, select Choose what to clear.</span></span>
- <span data-ttu-id="b2a6b-110">쿠키 및 저장 된 웹 사이트 데이터 확인란을 선택 하 고 지우기를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-110">Select the Cookies and saved website data check box and select Clear.</span></span>

<span data-ttu-id="b2a6b-111">**참고**: Firefox, Chrome 등의 다른 브라우저를 사용 하는 경우에는 이러한 단계가 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b2a6b-111">**Note**: These steps may differ when using other browsers such as Firefox or Chrome.</span></span>

