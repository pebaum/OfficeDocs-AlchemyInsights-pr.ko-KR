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
ms.openlocfilehash: a943c59d67c512e6326856dacd0053db121f6aa3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36542002"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="8ec34-102">기본 전자 메일 주소를 설정 하거나 사용자 특성을 변경할 수 없음</span><span class="sxs-lookup"><span data-stu-id="8ec34-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="8ec34-103">환경에 대해 디렉터리 동기화를 사용 하도록 설정 된 경우에는 Microsoft 365 관리 센터를 사용 하 여 일부 사용자 또는 개체 특성을 변경할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="8ec34-103">If directory synchronization is enabled for your environment, some user or object attributes cannot be changed using the Microsoft 365 admin center.</span></span>

<span data-ttu-id="8ec34-104">동기화 된 사용자 및 모든 해당 특성을 완전히 관리 하려면 로컬 active directory 사용자 및 그룹 관리 콘솔 (adsiedit)을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="8ec34-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="8ec34-105">또는 다음과 같은 일반적인 예와 같이 powershell을 사용 하 여 동기화 된 사용자에 대 한 개별 사용자 또는 특성을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8ec34-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="8ec34-106">Get-msoluser-UserPrincipalName user@yourdomain.onmicrosoft.com-AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8ec34-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="8ec34-107">Get-msoluser-UserPrincipalName "user@yourdomain.onmicrosoft.com"-DisplayName "테스트 사용자"-LastName "사용자"-제목 "관리자"-부서 "HR"</span><span class="sxs-lookup"><span data-stu-id="8ec34-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="8ec34-108">Get-msoluser-UserPrincipalName "user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8ec34-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>