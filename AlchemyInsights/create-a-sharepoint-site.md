---
title: SharePoint 사이트 만들기
ms.author: kirks
author: Techwriter40
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: a4c6029c632178136396a91ba9754752dc8f7180
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32407620"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="91afb-102">SharePoint 사이트 만들기</span><span class="sxs-lookup"><span data-stu-id="91afb-102">Create a SharePoint site</span></span>

<span data-ttu-id="91afb-103">사이트 만들기 옵션 [은 새 SharePoint 관리 센터에서 사이트 관리](https://docs.microsoft.com/sharepoint/manage-site-creation ) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="91afb-103">See [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation ) for site creation options.</span></span> <span data-ttu-id="91afb-104">[팀 사이트](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) 를 만들려면 (Office 365 그룹을 만들) 또는 [통신 사이트](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb)를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="91afb-104">Select to create a [team site](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) (which will create an Office 365 group) or a [communication site](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb).</span></span> <span data-ttu-id="91afb-105">[클래식 사이트](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site)를 만들거나 Office 365 그룹이 포함 되지 않은 새 팀 사이트를 만들려면 **기타 옵션**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="91afb-105">To create a [classic site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site), or a new team site that doesn't include an Office 365 group, click **Other options**.</span></span> 
  
<span data-ttu-id="91afb-106">정보</span><span class="sxs-lookup"><span data-stu-id="91afb-106">Tips:</span></span>
- <span data-ttu-id="91afb-107">*기존 사이트와 동일한 URL을 사용 하 여 사이트를 만들 수는 없습니다. 사이트를 삭제 하 고 해당 URL을 다시 사용 하려는 경우 삭제 된 사이트 아래에 해당 사이트가 계속 남아 있을 수 있습니다 \*\*\*\*. 삭제 된 사이트를 관리 하려면 [사이트 삭제](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site)를 참조 하세요. Powershell을 사용 하 여 사이트를 완전히 제거 하려면 [제거-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet 예제를 참조 하세요.*</span><span class="sxs-lookup"><span data-stu-id="91afb-107">*You cannot create a site with the same URL of an existing site. If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**. To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site). To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.*</span></span>
- <span data-ttu-id="91afb-108">*일부 사용자가 사이트를 만들지 못할 수 있습니다. [SharePoint Online에서 사이트 만들기 관리를](https://docs.microsoft.com/sharepoint/manage-site-creation)참조 하세요.*</span><span class="sxs-lookup"><span data-stu-id="91afb-108">*Some users may not be able to create a site. See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).*</span></span>
- <span data-ttu-id="91afb-109">*사이트가 예상 보다 오래 **생성** 되는 것 처럼 표시 될 수 있습니다. 이 문제가 처음 발생 한 것으로 24 시간 이상 경과 된 경우 지원 티켓을 기록 하세요. 대부분의 경우에는 이미 솔루션을 사용 하 고 있습니다. 솔루션을 완료 하려면 최소한 24 시간 이상 기다려 주세요.*</span><span class="sxs-lookup"><span data-stu-id="91afb-109">*It's possible the site appears stuck at **Creating** longer than expected. If more than 24 hours have passed since you first saw this issue, please log a support ticket. In many cases, we're already working on a solution. Please give us at least 24 hours to complete a solution.*</span></span>
