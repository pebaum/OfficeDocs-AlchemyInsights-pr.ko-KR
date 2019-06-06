---
title: 사용자에 게 SharePoint 및 OneDrive에 대 한 액세스 권한 부여
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 9326932e93970edc96396a141c9b36b14e7b4d4d
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736653"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="15e79-102">사용자에 게 SharePoint 및 OneDrive에 대 한 액세스 권한 부여</span><span class="sxs-lookup"><span data-stu-id="15e79-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="15e79-103">이 문제는 사용자가 삭제 되 고 동일한 UPN (사용자 계정 이름)으로 다시 만들어지는 경우에 가장 자주 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="15e79-104">새 계정은 다른 PUID (Passport 고유 ID) 값을 사용 하 여 만들어집니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="15e79-105">사용자가 사이트 모음 또는 OneDrive에 액세스 하려고 하면 사용자에 게 잘못 된 PUID가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="15e79-106">두 번째 시나리오에는 Active Directory OU (조직 구성 단위)와의 디렉터리 동기화가 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="15e79-107">사용자가 이미 SharePoint에 로그인 한 후 다른 OU로 이동 하 고 SharePoint를 사용 하 여 resynced이 문제가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="15e79-108">이 문제를 해결 하려면[Office 365에서 사용자 복원](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide)문서의 단계와 함께 원래 UPN을 복원 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="15e79-109">이 작업을 완료 한 후에는 [사용자의 onedrive에 대해 관리자를 추가](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive) 하는 단계를 수행 하 여 사용자에 게 OneDrive 사이트에 대 한 관리자 권한이 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15e79-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="15e79-110">사용 권한 수준에 대 한 자세한 내용은 [SharePoint의 사용 권한 수준 이해](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels)문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="15e79-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>
