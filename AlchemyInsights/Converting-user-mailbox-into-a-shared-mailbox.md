---
title: 사용자 사서함 공유 사서함 변환 되어 있습니까?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478000"
---
사용자가 Exchange 라이선스 하는 경우 사용자 사서함 공유 사서함을 변환할 수 있습니다. 사서함을 변환한 후에 표시 되려면 활성 사용자 목록에서 해당 목록에는 공유 사서함 포함 되어 있으므로 계속 됩니다. 그러나 변환 된 사서함 공유 사서함 목록에는도 표시 됩니다. 
  
Exchange 관리 콘솔의 사서함으로 변환 하려고 하면 변환이 실패 하는 경우 브라우저 캐시 및 쿠키의 선택을 취소 하 고 다시 시도 하십시오. 여전히 작동 하지 않는 경우 다음 명령을 실행 하 여 Exchange 관리 셸에서 사서함 변환 (영문) 시도 하십시오.
  
```
Set-Mailbox -Type Shared
```

더 많은 사서함 변환 정보는 [공유 사서함을 사용자 사서함으로 변환](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba)에 사용할 수 있습니다.
  
