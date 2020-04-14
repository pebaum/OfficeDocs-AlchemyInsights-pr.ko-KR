---
title: 강력한 암호 요구 사항 변경
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 21f80a7cc8b00ac56acdb05add1e1bfdfac9d827
ms.sourcegitcommit: c061f1dfa6f557a9ec083dd030b73b121d9864ea
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/14/2020
ms.locfileid: "43286270"
---
# <a name="change-strong-password-requirement"></a>강력한 암호 요구 사항 변경

Microsoft는 기본적으로 강력한 암호를 요구 합니다. 

PowerShell을 사용 하 여 다음 명령을 사용 하 여 특정 사용자에 대해 강력한 암호를 사용 하지 않도록 설정할 수 있습니다.<br>
*Get-msoluser-UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*

- [암호 정책에 대 한 추가 정보](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [PowerShell을 사용 하 여 Office 365에 연결 하는 방법](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [PowerShell Get-msoluser 명령에 대 한 추가 정보](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
- [사용자 암호를 만료 기한 제한 없음으로 설정](https://docs.microsoft.com/microsoft-365/admin/add-users/set-password-to-never-expire)
