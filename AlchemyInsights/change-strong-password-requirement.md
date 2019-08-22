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
ms.openlocfilehash: f8790a26ec7c5de57f5dbfc9e1c162767c599f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36518765"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="70493-102">강력한 암호 요구 사항 변경</span><span class="sxs-lookup"><span data-stu-id="70493-102">Change strong password requirement</span></span>

<span data-ttu-id="70493-103">Microsoft는 기본적으로 강력한 암호를 요구 합니다.</span><span class="sxs-lookup"><span data-stu-id="70493-103">Microsoft requires strong passwords by default.</span></span> 

<span data-ttu-id="70493-104">PowerShell을 사용 하 여 다음 명령을 사용 하 여 특정 사용자에 대해 강력한 암호를 사용 하지 않도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="70493-104">Using PowerShell, you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="70493-105">*Get-msoluser-UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="70493-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="70493-106">암호 정책에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="70493-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="70493-107">PowerShell을 사용 하 여 Office 365에 연결 하는 방법</span><span class="sxs-lookup"><span data-stu-id="70493-107">How to connect to Office 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="70493-108">PowerShell Get-msoluser 명령에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="70493-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)