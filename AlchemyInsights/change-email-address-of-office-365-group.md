---
title: Microsoft 365 그룹의 전자 메일 주소 변경하기
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 0a07e6279f533a4c26a4e90c10651421a5df8860
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/27/2020
ms.locfileid: "44282470"
---
# <a name="change-email-address-of-an-microsoft-365-group"></a>Microsoft 365 그룹의 전자 메일 주소 변경하기

관리 센터를 사용하여 Microsoft 365 그룹의 전자 메일 주소를 변경할 수 있습니다. 그룹을 선택하고 @전자 메일 주소 편집을 선택하면 됩니다.

다음 EXO PowerShell 명령을 사용하여 Microsoft 365 그룹의 기본 SMTP 주소를 변경할 수도 있습니다.

Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>

예제:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
