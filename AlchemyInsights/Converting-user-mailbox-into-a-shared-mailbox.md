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
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32374329"
---
<span data-ttu-id="98881-102">사용자에 게 Exchange 라이선스가 있는 경우에만 사용자 사서함을 공유 사서함으로 변환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="98881-102">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="98881-103">사서함이 변환 된 후에는 해당 목록에 공유 사서함이 포함 되므로 활성 사용자 목록에 계속 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="98881-103">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="98881-104">그러나 변환 된 사서함은 공유 사서함 목록에도 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="98881-104">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="98881-105">Exchange 관리 콘솔에서 사서함을 변환 하는 동안 변환이 실패 하는 경우 브라우저 캐시 및 쿠키를 지우고 다시 시도 합니다.</span><span class="sxs-lookup"><span data-stu-id="98881-105">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="98881-106">여전히 작동 하지 않으면 다음 명령을 실행 하 여 Exchange 관리 셸에서 사서함을 변환 해 봅니다.</span><span class="sxs-lookup"><span data-stu-id="98881-106">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="98881-107">더 많은 사서함 변환 정보를 사용할 수 있습니다. [사용자 사서함을 공유 사서함으로 변환](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba)합니다.</span><span class="sxs-lookup"><span data-stu-id="98881-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  
