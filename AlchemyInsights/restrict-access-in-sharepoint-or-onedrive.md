---
title: SharePoint 또는 OneDrive에 대 한 액세스를 제한 합니다.
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: b6be074ed5f7e83f8196ca3fe90252673896569f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299251"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="6b223-102">SharePoint 또는 OneDrive에 대 한 액세스를 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b223-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="6b223-p101">SharePoint와 OneDrive에서 그룹이 나 한 액세스 권한을 부여할 개인 에게만 액세스 권한을 부여 하 여 파일, 폴더 및 목록 등과 같은 항목에 대 한 액세스를 제한 합니다. 기본적으로 계층 구조에 더 높은 위쪽에서 sharepoint에서 사용 권한 상속 됩니다. 따라서 파일을 사이트에서 사용 권한을 상속 하는 라이브러리에서 사용 권한을 상속 하는 폴더에서 사용 권한을 상속 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b223-p101">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access. By default, permissions in SharePoint are inherited from higher up in the hierarchy. So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="6b223-p102">더 높은 수준에서 공유할 수 있습니다 (와 같은 전체 사이트를 공유 하 여) 한 다음 사이트에서 모든 항목을 공유 하지 않으려면 상속 합니다. 그러나 하지 것이 좋습니다이 사용 권한을 더 복잡 하 고 혼란을 야기할 나중에 유지 하므로 합니다. 수 수행할 대신 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="6b223-p102">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site. However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future. Here's what you could do instead:</span></span>
  
- <span data-ttu-id="6b223-109">예에 하나의 파일을 제외 하 고 폴더의 모든 콘텐츠를 공유 하려는, 하는 경우 해당 파일을 공유 되지 않은 새 위치로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b223-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="6b223-110">두 하위 폴더는 폴더에 있는 그룹 A와 B와 하나의 하위 폴더를 공유 하 고 두번째 하위 폴더에 그룹 A 액세스만 허용, 그룹 A와 상위 폴더를 공유 및 그룹 B 첫번째 하위 폴더에 추가 하려는 경우.</span><span class="sxs-lookup"><span data-stu-id="6b223-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="6b223-111">파일 또는 폴더 공유 중지</span><span class="sxs-lookup"><span data-stu-id="6b223-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

