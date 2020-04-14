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
# <a name="change-strong-password-requirement"></a><span data-ttu-id="5e84b-102">강력한 암호 요구 사항 변경</span><span class="sxs-lookup"><span data-stu-id="5e84b-102">Change strong password requirement</span></span>

<span data-ttu-id="5e84b-103">Microsoft는 기본적으로 강력한 암호를 요구 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e84b-103">Microsoft requires strong passwords by default.</span></span> 

<span data-ttu-id="5e84b-104">PowerShell을 사용 하 여 다음 명령을 사용 하 여 특정 사용자에 대해 강력한 암호를 사용 하지 않도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5e84b-104">Using PowerShell, you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="5e84b-105">*Get-msoluser-UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="5e84b-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="5e84b-106">암호 정책에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="5e84b-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="5e84b-107">PowerShell을 사용 하 여 Office 365에 연결 하는 방법</span><span class="sxs-lookup"><span data-stu-id="5e84b-107">How to connect to Office 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="5e84b-108">PowerShell Get-msoluser 명령에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="5e84b-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
- [<span data-ttu-id="5e84b-109">사용자 암호를 만료 기한 제한 없음으로 설정</span><span class="sxs-lookup"><span data-stu-id="5e84b-109">Set an individual user's password to never expire</span></span>](https://docs.microsoft.com/microsoft-365/admin/add-users/set-password-to-never-expire)
