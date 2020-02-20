---
title: CompletedWithErrors 상태인 공용 폴더 마이그레이션 일괄 처리의 경우
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
- "3532"
ms.openlocfilehash: 739e9d91f90e4c0374814d199e4372eb5625553a
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158618"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="013dc-102">CompletedWithErrors 상태인 공용 폴더 마이그레이션 일괄 처리의 경우</span><span class="sxs-lookup"><span data-stu-id="013dc-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="013dc-103">다음 단계에 따라 큰/잘못 된 항목을 건너뛰어 일괄 처리를 완료 합니다.</span><span class="sxs-lookup"><span data-stu-id="013dc-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="013dc-104">마이그레이션 일괄 처리에서 건너뛴 항목을 승인 합니다.</span><span class="sxs-lookup"><span data-stu-id="013dc-104">Approve the skipped items on migration batch:</span></span>

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. <span data-ttu-id="013dc-105">다음 명령을 사용 하 여 "동기화" 되었지만 완료 되지 않은 마이그레이션 요청에 대해 건너뛴 항목을 승인 합니다.</span><span class="sxs-lookup"><span data-stu-id="013dc-105">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. <span data-ttu-id="013dc-106">마이그레이션 일괄 처리 및 요청이 몇 분 후에 다시 시작 되 고 완료 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="013dc-106">The migration batch and requests should resume and complete in a few minutes.</span></span>

