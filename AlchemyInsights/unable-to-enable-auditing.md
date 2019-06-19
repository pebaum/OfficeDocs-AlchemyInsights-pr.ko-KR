---
title: 2419-사용할 수 없음 감사
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 3af01c03711eed646f0009afb5bea685bc358196
ms.sourcegitcommit: 87153fec6f6468b57893abf4aac073ba4068e67b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/19/2019
ms.locfileid: "35065665"
---
# <a name="unable-to-enable-unified-auditing"></a><span data-ttu-id="8b78a-102">통합 감사를 사용 하도록 설정할 수 없음</span><span class="sxs-lookup"><span data-stu-id="8b78a-102">Unable to enable unified auditing</span></span>

<span data-ttu-id="8b78a-103">Office 365 조직에 대해 통합 감사를 사용 하도록 설정 하려고 하면 다음과 비슷한 오류가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-103">When you try to enable unified auditing for your Office 365 organization, you may receive an error similar the following:</span></span>

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

<span data-ttu-id="8b78a-104">이 문제를 해결 하려면 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-104">To resolve this issue, follow these steps:</span></span>

1. <span data-ttu-id="8b78a-105">[Exchange Online Powershell에 연결](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell)합니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-105">[Connect to Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="8b78a-106">다음 cmdlet을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-106">Run the following cmdlet:</span></span>

   ```
   Enable-OrganizationCustomization
   ```

3. <span data-ttu-id="8b78a-107">이전 설정이 적용 되려면 60 분 정도 기다립니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-107">Wait for 60 minutes for the previous setting to take effect.</span></span>

4. <span data-ttu-id="8b78a-108">Exchange Online PowerShell에서 다음 명령을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="8b78a-108">Run the following command in Exchange Online PowerShell:</span></span>

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

<span data-ttu-id="8b78a-109">자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="8b78a-109">For additional information, see the following articles:</span></span>

- [<span data-ttu-id="8b78a-110">다단계 인증을 사용하여 Exchange Online PowerShell에 연결</span><span class="sxs-lookup"><span data-stu-id="8b78a-110">Connect to Exchange Online PowerShell using multi-factor authentication</span></span>](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [<span data-ttu-id="8b78a-111">Office 365 감사 로그 검색 켜기 또는 끄기</span><span class="sxs-lookup"><span data-stu-id="8b78a-111">Turn Office 365 audit log search on or off</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)
