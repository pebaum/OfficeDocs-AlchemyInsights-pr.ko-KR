---
title: 액세스 거부 메시지 문제 해결
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 1930edcfd14acc48ea77b66e2793654a3e6332cc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759806"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="fd7bd-102">액세스 거부 메시지 문제 해결</span><span class="sxs-lookup"><span data-stu-id="fd7bd-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="fd7bd-103">다른 사용자가 SharePoint의 공유 폴더에 "액세스 거부" 라는 메시지를 받은 경우 사이트 모음 관리자가 "제한 된 액세스 사용자 권한 잠금 모드"를 사용 하도록 설정 했을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="fd7bd-104">이 기능을 해제 하려면:</span><span class="sxs-lookup"><span data-stu-id="fd7bd-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="fd7bd-105">사이트로 이동 하 고 설정 아이콘을 클릭 한 다음 **사이트 설정을**클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="fd7bd-106">**사이트 모음 관리**에서 **사이트 모음 기능**을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="fd7bd-107">제한 된 **액세스 사용자 권한 잠금 모드**옆에 있는 **비활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="fd7bd-108">사이트가 게시 사이트인 경우 공유 폴더에 대해서도 액세스 거부 메시지가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="fd7bd-109">자세한 내용은 [공유 폴더 액세스 시 액세스 거부](https://go.microsoft.com/fwlink/?linkid=2004317)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="fd7bd-110">액세스 요청을 보려고 할 때 "액세스 거부" 라는 메시지가 표시 되 면 사용자를 사이트 모음 관리자 또는 사이트 소유자 그룹의 구성원으로 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="fd7bd-111">자세한 내용은 액세스가 [거부 됨 액세스 요청 목록을](https://go.microsoft.com/fwlink/?linkid=2004220)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="fd7bd-112">사용자가 Active Directory에서 온-프레미스를 제거한 후 다시 추가 된 "액세스 거부" 메시지를 받은 경우 [사용자 계정이 Microsoft 365와 동기화 되 면 액세스 거부](https://go.microsoft.com/fwlink/?linkid=2004318)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="fd7bd-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

