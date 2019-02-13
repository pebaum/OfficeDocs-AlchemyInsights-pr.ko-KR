---
title: 작동 하지 않는 Exchange 관리 센터에서 보존 정책
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: c9061fa728edaab6575a7b1027783e56739a6d14
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29934998"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="788f5-102">Exchange 관리 센터의 보존 정책</span><span class="sxs-lookup"><span data-stu-id="788f5-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="788f5-103">**문제:** 새로 만든 또는 사서함에 Exchange 관리 센터에서 업데이트 된 보존 정책 적용 하지 않는 또는 항목 보관 사서함으로 이동 하거나 삭제 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="788f5-104">**루트 원인은 다음과 같습니다.**</span><span class="sxs-lookup"><span data-stu-id="788f5-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="788f5-p101">다음은 **관리 되는 폴더 도우미가** 처리 되지 않은 사용자의 사서함 때문일 수 있습니다. 관리 되는 폴더 도우미 하려고 시도 하면 7 일 마다 클라우드 기반 조직에서 모든 사서함을 처리 합니다. 사서함을 처리 하는 관리 되는 폴더는 데 도움이 또는 관리 되는 폴더 도우미가 특정 프로세스를 시작 하려면 Start-managedfolderassistant cmdlet을 실행할 수 때까지 기다릴 수를 보존 태그를 변경 하거나 사서함에 다른 보존 정책을 적용 하는 경우 사서함입니다. 이 cmdlet을 실행 하는 것은 테스트 또는 보존 정책 또는 보존 태그 설정 문제를 해결 하는데 유용 합니다. 자세한 내용은 [관리 되는 폴더 도우미가 실행](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist)을 참고 하십시오.</span><span class="sxs-lookup"><span data-stu-id="788f5-p101">This may be because the **Managed Folder Assistant** has not processed the user's mailbox. The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days. If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox. Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings. For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="788f5-110">**솔루션:** 관리 되는 폴더 도우미가 특정 사서함에 대 한 시작 하려면 다음 명령을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span> 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="788f5-p102">이 작업 수 있습니다 **RetentionHold** 의 사서함에서 **사용 하도록 설정** 된 경우에 발생할 수 있습니다. 사서함을 RetentionHold에 배치 된 사서함에 보존 정책은 시간 동안 처리 되지 않습니다. RetentionHold 설정 참조에서 자세한 정보에 대 한: [사서함 보존](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold)합니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-p102">This may also be occur if **RetentionHold** has been **enabled** on the mailbox. If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time. For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="788f5-114">**해결 방법:**</span><span class="sxs-lookup"><span data-stu-id="788f5-114">**Solution:**</span></span>
    
  - <span data-ttu-id="788f5-115">[EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps)에서 특정 사서함의 RetentionHold 설정의 상태를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="788f5-116">특정 사서함에 RetentionHold를 **사용 하지 않도록 설정** 하려면 다음 명령을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span> 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="788f5-117">이제, 관리 되는 폴더 도우미를 다시 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="788f5-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="788f5-118">**참고:** 사서함 10MB 보다 작으면, 관리 되는 폴더 도우미가 자동으로 처리 됩니다 사서함.</span><span class="sxs-lookup"><span data-stu-id="788f5-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span> 
  

