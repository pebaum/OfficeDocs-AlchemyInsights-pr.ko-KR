---
title: 보관 사서함으로 전자 메일 메시지 이동
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 37f256ef31402f5139fdd7c2af8f3a6ca9dc3525
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32418327"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="c9327-102">보관 사서함으로 전자 메일 이동</span><span class="sxs-lookup"><span data-stu-id="c9327-102">Move email to the archive mailbox</span></span>
 
1. <span data-ttu-id="c9327-103">**보관 사서함** 이 사용 하도록 설정 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="c9327-104">그렇지 않으면 [이 문서의](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) 단계를 사용 하 여 보관 사서함을 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="c9327-105">보관 사서함에 메시지를 자동으로 보관 하려면 **보관 함으로 이동** 작업이 있는 보존 태그가 **전체 사서함에 자동으로 적용 (기본값) 태그**를 설정 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="c9327-106">여기에 나오는 단계를 사용 하 여 [Default to Archive 태그](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0)를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-106">Use the steps here to create the tag: [Archive Default tag](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span></span>
    
3. <span data-ttu-id="c9327-107">다음으로, **보관** 태그를 보존 정책에 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="c9327-108">Exchange 관리 센터에서 **보존 정책** >을 선택 하 고 **보관 함으로 이동 태그** 를 > **저장**정책에 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span> 
    
4. <span data-ttu-id="c9327-109">이제 특정 사용자의 사서함에 [보존 정책을 할당](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="c9327-110">**기본** 및 **보관** 사서함 모두에 동일한 정책이 적용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span> 
    
<span data-ttu-id="c9327-111">MFA (관리 되는 폴더 도우미)를 강제로 실행 하 고 사용자 사서함에 새 설정을 적용 해야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="c9327-112">[exo PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) 된 동안 다음 명령을 실행 하 여 특정 사서함에 대해 관리 되는 폴더 도우미를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="c9327-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span> 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

<span data-ttu-id="c9327-113">보관 정책 설정에 대 한 자세한 내용은 [사서함에 대 한 보관 및 삭제 정책](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)설정을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c9327-113">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  

