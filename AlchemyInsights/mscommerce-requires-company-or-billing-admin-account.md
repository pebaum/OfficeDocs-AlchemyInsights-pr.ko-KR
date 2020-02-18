---
title: MSCommerce 모듈에 연결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3529"
ms.openlocfilehash: 80735a03eef6ef9f7b791c43019678ea01f83c00
ms.sourcegitcommit: 9db3be25d088b8d4b2d476aeace79e653ca0a421
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/17/2020
ms.locfileid: "42093592"
---
# <a name="mscommerce-requires-a-company-or-billing-administrator-account"></a><span data-ttu-id="9bec2-102">MSCommerce에는 회사 또는 청구 관리자 계정이 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="9bec2-102">MSCommerce requires a Company or Billing Administrator account</span></span>

<span data-ttu-id="9bec2-103">MSCommerce 모듈에는 회사 또는 청구 관리자 권한이 있는 계정이 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="9bec2-103">The MSCommerce module requires an account with Company or Billing Administrator privileges.</span></span> <span data-ttu-id="9bec2-104">다음 오류가 발생 하는 경우 다른 계정을 사용 하 여 다시 연결 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9bec2-104">If you are receiving the following error, you will need to reconnect with a different account.</span></span>

    ErrorMessage - The remote server returned an error: (403) Forbidden. ErrorDetails - 
    At C:\Program Files\WindowsPowerShell\Modules\MSCommerce\1.2\MSCommerce.psm1:216 char:5
    +     HandleError -ErrorContext $_ -CustomErrorMessage "Failed to retri ...
    +     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        + CategoryInfo          : NotSpecified: (:) [Write-Error], WriteErrorException
        + FullyQualifiedErrorId : Microsoft.PowerShell.Commands.WriteErrorException,HandleError

<span data-ttu-id="9bec2-105">사용자의 계정에 회사 또는 청구 관리자 권한이 없는 경우 IT 관리자에 게 문의 하세요.</span><span class="sxs-lookup"><span data-stu-id="9bec2-105">If your account does not have Company or Billing Administrator privileges, contact your IT Admin.</span></span>
