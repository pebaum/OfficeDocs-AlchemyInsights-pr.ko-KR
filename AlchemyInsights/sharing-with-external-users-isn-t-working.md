---
title: 외부 사용자와 공유가 작동 하지 않습니다.
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478108"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="f4b96-102">외부 사용자와 SharePoint 콘텐츠를 공유 하는 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="f4b96-103">외부 공유 켜져 조직에 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="f4b96-104">이동 하는 [서비스 &amp; Office 365 관리 센터에서 추가 기능 페이지](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), **사이트**를 클릭 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-104">Go to the [Services &amp; add-ins page in the Office 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="f4b96-p101">"On"으로 설정 되어 있는지 확인 "기존 외부 사용자만" 선택 하는 경우 외부 사용자는 Office 365 관리 센터에 나열 되어있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-p101">Make sure the setting is turned to "On." If "Only existing external users" is selected, make sure the external user is listed in the Office 365 admin center.</span></span>
    
<span data-ttu-id="f4b96-p102">전화번호를 공유 하는 외부 사이트에 대 한 켜져 있는지 확인 하십시오. 클래식 사이트 모음:</span><span class="sxs-lookup"><span data-stu-id="f4b96-p102">Make sure external sharing it turned on for the site. For a classic site collection:</span></span>
  
1. <span data-ttu-id="f4b96-109">클래식 SharePoint 관리 센터의 왼쪽된 창에서 **사이트 모음**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-109">In the classic SharePoint admin center, in the left pane, click **site collections**.</span></span>
    
2. <span data-ttu-id="f4b96-110">사이트 또는 사이트를 선택 하 고 리본 메뉴에서 **공유**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="f4b96-111">Office 365 그룹에 속해 있는 팀 사이트 또는 통신 사이트:</span><span class="sxs-lookup"><span data-stu-id="f4b96-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="f4b96-p103">이러한 새 사이트 유형 조직 전체의 설정을 로그인 필요 하지 않은 링크를 사용 하 여 파일 공유를 허용 하지 않는 한는 동일한 공유를 설정 하면 조직 전체의 설정으로 포함 합니다. 이 경우 사이트에 로그인 하는 기존 및 새 외부 사용자와 공유를 허용 합니다. 특정 사이트에 대 한 설정을 변경 하려면 새 SharePoint 관리 센터 (미리 보기) 또는 PowerShell을 사용 합니다. [자세한 내용](https://go.microsoft.com/fwlink/?linkid=871863)입니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-p103">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in. In this case, the sites allow sharing with new and existing external users who sign in. To change the setting for specific sites, use the new SharePoint admin center (preview) or PowerShell. [Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="f4b96-116">모든 사이트에 대 한 외부 공유 설정을 조직 차원의 설정 보다 더 하지 허용 하지만 조직 차원의 설정에 권한 보다 제한적인 하나일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f4b96-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

