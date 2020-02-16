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
ms.openlocfilehash: 4243cdf0170fed1eadac6560d2a04e1a861c63e5
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/15/2020
ms.locfileid: "42043599"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="0640c-102">CompletedWithErrors 상태인 공용 폴더 마이그레이션 일괄 처리의 경우</span><span class="sxs-lookup"><span data-stu-id="0640c-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="0640c-103">다음 단계에 따라 큰/잘못 된 항목을 건너뛰어 일괄 처리를 완료 합니다.</span><span class="sxs-lookup"><span data-stu-id="0640c-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="0640c-104">마이그레이션 일괄 처리에서 건너뛴 항목을 승인 합니다.</span><span class="sxs-lookup"><span data-stu-id="0640c-104">Approve the skipped items on migration batch:</span></span>

    <span data-ttu-id="0640c-105">New-migrationbatch \<batchname>-ApproveSkippedItems</span><span class="sxs-lookup"><span data-stu-id="0640c-105">Set-MigrationBatch \<batchname> -ApproveSkippedItems</span></span> 
2. <span data-ttu-id="0640c-106">다음 명령을 사용 하 여 "동기화" 되었지만 완료 되지 않은 마이그레이션 요청에 대해 건너뛴 항목을 승인 합니다.</span><span class="sxs-lookup"><span data-stu-id="0640c-106">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    <span data-ttu-id="0640c-107">$pf = Get-Get-publicfoldermailboxmigrationrequest | Get-publicfoldermailboxmigrationrequeststatistics-에서는 includereport; ForEach ($i $pf) {if ($i LargeItemsEncountered-gt 0-또는 $i. Bad항목 발견-gt 0) {Get-publicfoldermailboxmigrationrequest $i. IdentifyingGuid-SkippedItemApprovalTime $ ([DateTime]:: UtcNow)}}</span><span class="sxs-lookup"><span data-stu-id="0640c-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}</span></span>
3. <span data-ttu-id="0640c-108">마이그레이션 일괄 처리 및 요청이 몇 분 후에 다시 시작 되 고 완료 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0640c-108">The migration batch and requests should resume and complete in a few minutes.</span></span>

