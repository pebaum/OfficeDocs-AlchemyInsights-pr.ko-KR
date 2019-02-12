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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29932838"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="2d0b0-102">SharePoint 사이트 만들기</span><span class="sxs-lookup"><span data-stu-id="2d0b0-102">Create a SharePoint site</span></span>

<span data-ttu-id="2d0b0-p101">사이트 만들기 옵션에 대 한 [새 SharePoint 관리 센터에서 관리 사이트](https://docs.microsoft.com/sharepoint/manage-site-creation ) 를 참조 하십시오. (하는 Office 365 그룹 만듭니다)는 [팀 사이트](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) 또는 [통신 사이트](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb)를 만들려면이 옵션을 선택 합니다. [클래식 사이트](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site)또는 Office 365 그룹에 포함 되지 않은 새 팀 사이트를 만들려면 **다른 옵션**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d0b0-p101">See [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation ) for site creation options. Select to create a [team site](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) (which will create an Office 365 group) or a [communication site](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb). To create a [classic site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site), or a new team site that doesn't include an Office 365 group, click **Other options**.</span></span> 
  
<span data-ttu-id="2d0b0-106">팁:</span><span class="sxs-lookup"><span data-stu-id="2d0b0-106">Tips:</span></span>
- <span data-ttu-id="2d0b0-107">*기존 사이트의 동일한 URL로 사이트를 만들 수 없습니다. 사이트를 삭제 하 고 다시 URL을 사용 하고자 하는 경우에 **삭제 된 사이트**에서 여전히 존재 하는 삭제 된 사이트 가능한 합니다. 관리 [사이트를 삭제](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site)하는 사이트 참조를 삭제 합니다. Powershell 사용 하 여 사이트를 완전히 제거 하려면 [제거 SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet 예제를 참조 하십시오.*</span><span class="sxs-lookup"><span data-stu-id="2d0b0-107">*You cannot create a site with the same URL of an existing site. If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**. To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site). To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.*</span></span>
- <span data-ttu-id="2d0b0-108">*일부 사용자에 게 사이트를 만들지 못할 수 있습니다. [SharePoint Online에서 관리 사이트 만들기](https://docs.microsoft.com/sharepoint/manage-site-creation)를 참조 하십시오.*</span><span class="sxs-lookup"><span data-stu-id="2d0b0-108">*Some users may not be able to create a site. See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).*</span></span>
- <span data-ttu-id="2d0b0-109">*사이트 **만들기** 예상 보다 오래에서 눌려 것 같습니다. 이 문제를 처음으로 본 이후 24 시간 이상 경과, 지원 티켓을 기록 하십시오. 대부분의 경우에는 이미 작업 중인 솔루션을 합니다. 솔루션을 완료 하려면 최소한 24 시간을 보내 주십시오.*</span><span class="sxs-lookup"><span data-stu-id="2d0b0-109">*It's possible the site appears stuck at **Creating** longer than expected. If more than 24 hours have passed since you first saw this issue, please log a support ticket. In many cases, we're already working on a solution. Please give us at least 24 hours to complete a solution.*</span></span>
