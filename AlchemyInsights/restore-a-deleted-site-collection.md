---
title: 삭제된 사이트 모음 복원
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: 1f9a66daf7bee43291b785b6260aec8725ee782f
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30753792"
---
# <a name="restore-a-deleted-site-collection"></a><span data-ttu-id="7292a-102">삭제된 사이트 모음 복원</span><span class="sxs-lookup"><span data-stu-id="7292a-102">Restore a deleted site collection</span></span>

<span data-ttu-id="7292a-103">관리자가 클래식 사이트 모음을 삭제 하면 사이트가 영구적으로 삭제 되기 전까지 93 일 전에 보관 되는 사이트 모음 휴지통에 저장 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-103">When an admin deletes a classic site collection, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="7292a-104">사이트 모음을 복원 하려면</span><span class="sxs-lookup"><span data-stu-id="7292a-104">To restore the site collection:</span></span>
  
1. <span data-ttu-id="7292a-105">클래식 SharePoint 관리 센터에서 리본 메뉴의 **휴지통** 을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-105">In the classic SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="7292a-106">복원 하려는 사이트 모음 옆에 있는 확인란을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="7292a-107">**지운 편지함 복원을**클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="7292a-108">삭제 된 통신 사이트를 복원 하려면 새 SharePoint 관리 센터 미리 보기를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-108">To restore a deleted communication site, you can use the new SharePoint admin center preview.</span></span> <span data-ttu-id="7292a-109">그렇지 않은 경우에는 PowerShell을 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-109">Otherwise, you need to use PowerShell.</span></span> <span data-ttu-id="7292a-110">Office 365 그룹에 속하는 사이트를 복원 하려면 Exchange 관리 센터에서 그룹을 복원 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="7292a-111">그룹을 삭제 한 후 30 일 동안 복원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7292a-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

