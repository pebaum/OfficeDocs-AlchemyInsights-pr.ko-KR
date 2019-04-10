---
title: 외부 사용자와의 공유가 작동 하지 않음
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 69e290e5a13f40ad045086791189a7d0af88240b
ms.sourcegitcommit: 228c986911ecf73217116a5d1fdcd2e89362774e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2019
ms.locfileid: "31747604"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="4b9c1-102">외부 사용자와 SharePoint 콘텐츠를 공유 하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="4b9c1-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="4b9c1-103">조직에 대해 외부 공유가 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="4b9c1-104">[Microsoft 365 관리 센터 &amp; 에서 서비스 추가 기능 페이지로](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)이동 하 고 **사이트**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="4b9c1-105">설정이 "설정"으로 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="4b9c1-106">"기존 외부 사용자만"을 선택 하는 경우에는 외부 사용자가 Microsoft 365 관리 센터에 나열 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="4b9c1-107">사이트에 대 한 외부 공유를 설정 했는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="4b9c1-108">클래식 사이트 모음의 경우 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="4b9c1-109">새 SharePoint 관리 센터의 왼쪽 창에서 **사이트**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="4b9c1-110">사이트 또는 사이트를 선택 하 고 리본 메뉴에서 **공유**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="4b9c1-111">Office 365 그룹 또는 커뮤니케이션 사이트에 속하는 팀 사이트의 경우:</span><span class="sxs-lookup"><span data-stu-id="4b9c1-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="4b9c1-112">조직 차원의 설정에서 로그인이 필요 하지 않은 링크를 사용 하 여 파일을 공유할 수 있는 경우를 제외 하 고 이러한 새 사이트 유형은 조직 전체 설정과 동일한 공유 설정을 갖습니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="4b9c1-113">이 경우 사이트는 로그인 하는 신규 및 기존 외부 사용자와의 공유를 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="4b9c1-114">특정 사이트에 대 한 설정을 변경 하려면 새 SharePoint 관리 센터 또는 PowerShell을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="4b9c1-115">[자세한 정보](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="4b9c1-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="4b9c1-116">모든 사이트에 대 한 외부 공유 설정은 조직 차원의 설정 보다 더 제한적으로 사용할 수 있지만 조직 전체 설정 보다는 허용이 더 이상 가능 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="4b9c1-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

