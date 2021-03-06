---
title: 동기화 된 사용자 관리
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407356"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>기본 전자 메일 주소를 설정 하거나, 사용자 특성을 변경 하거나, 동기화 된 사용자를 제거/삭제할 수 없음

환경에 대해 디렉터리 동기화를 사용 하도록 설정 된 경우에는 Microsoft 365 관리 센터를 사용 하 여 일부 사용자 또는 개체 특성을 변경할 수 없습니다.

동기화 된 사용자 및 모든 해당 특성을 완전히 관리 하려면 로컬 active directory 사용자 및 그룹 관리 콘솔 (adsiedit)을 사용 합니다.  

또는 다음과 같은 일반적인 예와 같이 powershell을 사용 하 여 동기화 된 사용자에 대 한 개별 사용자 또는 특성을 변경할 수 있습니다. 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
