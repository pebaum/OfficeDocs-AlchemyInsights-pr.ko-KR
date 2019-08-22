---
title: 사용자 사서함을 공유 사서함으로 변환
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496441"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a><span data-ttu-id="075a0-102">사용자 메일 상자를 공유 사서함으로 변환</span><span class="sxs-lookup"><span data-stu-id="075a0-102">Convert a user mail box into a shared mailbox</span></span>

<span data-ttu-id="075a0-103">사용자에 게 Exchange 라이선스가 있는 경우에만 사용자 사서함을 공유 사서함으로 변환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-103">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="075a0-104">사서함이 변환 된 후에는 해당 목록에 공유 사서함이 포함 되므로 활성 사용자 목록에 계속 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-104">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="075a0-105">그러나 변환 된 사서함은 공유 사서함 목록에도 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-105">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="075a0-106">Exchange 관리 콘솔에서 사서함을 변환 하는 동안 변환이 실패 하는 경우 브라우저 캐시 및 쿠키를 지우고 다시 시도 합니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-106">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="075a0-107">여전히 작동 하지 않으면 다음 명령을 실행 하 여 Exchange 관리 셸에서 사서함을 변환 해 봅니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-107">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="075a0-108">더 많은 사서함 변환 정보를 사용할 수 있습니다. [사용자 사서함을 공유 사서함으로 변환](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox)합니다.</span><span class="sxs-lookup"><span data-stu-id="075a0-108">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span></span>
  
