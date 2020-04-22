---
title: 사서함 감사 사용
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: ae11d6be0789a5662d202b85268480a3d42922c4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703577"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="4f655-102">사서함 감사 사용</span><span class="sxs-lookup"><span data-stu-id="4f655-102">Enable mailbox auditing</span></span>

<span data-ttu-id="4f655-103">단일 사용자 또는 전체 조직에 대해 사서함 감사를 사용 하도록 설정 하려면 원격 전원 셸에서 다음 cmdlet을 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4f655-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="4f655-104">**단일 사용자**</span><span class="sxs-lookup"><span data-stu-id="4f655-104">**Single User**</span></span>
  
<span data-ttu-id="4f655-105">Set-Mailbox-Id "Jane Dow"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="4f655-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="4f655-106">**조직**</span><span class="sxs-lookup"><span data-stu-id="4f655-106">**Organization**</span></span>
  
<span data-ttu-id="4f655-107">Get-Mailbox-ResultSize 무제한-필터 {RecipientTypeDetails-eq "UserMailbox"} | Set-Mailbox-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="4f655-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="4f655-108">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="4f655-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

