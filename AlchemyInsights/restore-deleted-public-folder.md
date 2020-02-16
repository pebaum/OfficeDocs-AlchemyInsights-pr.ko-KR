---
title: 삭제 된 공용 폴더 복원
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063688"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="e5fdd-102">삭제 된 공용 폴더 복원</span><span class="sxs-lookup"><span data-stu-id="e5fdd-102">Restore a deleted public folder</span></span>

<span data-ttu-id="e5fdd-103">**공용 폴더에서 삭제 된 항목을 복원 하려면 다음을 수행 합니다**.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="e5fdd-104">[Outlook 2016의 메일 이외의 공용 폴더에서는 삭제 된 항목을 복구할 수 없습니다](https://aka.ms/pfrec).를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="e5fdd-105">**삭제 된 공용 폴더 (모든 유형)를 복원 하려면 다음을**수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="e5fdd-106">다음 EXO PowerShell 명령을 사용 하세요.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="e5fdd-107">구문:</span><span class="sxs-lookup"><span data-stu-id="e5fdd-107">Syntax:</span></span>

    ><span data-ttu-id="e5fdd-108">$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-재귀 |? {$_. Name-eq "\<name_of_deleted_public_Folder"}; Set-PublicFolder $pf. id-폴더가 \<복원 될 경로 경로></span><span class="sxs-lookup"><span data-stu-id="e5fdd-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored></span></span>

    <span data-ttu-id="e5fdd-109">예: 다음 명령은 Subfolder1를 복원 하 고 \Parent1 아래에 배치 합니다.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-109">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    ><span data-ttu-id="e5fdd-110">$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-재귀 |? {$_. Name-eq "Subfolder1"}; Set-PublicFolder $pf. identity-Path \Parent1</span><span class="sxs-lookup"><span data-stu-id="e5fdd-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1</span></span>

<span data-ttu-id="e5fdd-111">자세한 내용은 [삭제 된 공용 폴더 복원을](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="e5fdd-111">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
