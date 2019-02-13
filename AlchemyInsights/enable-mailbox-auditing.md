---
title: 사서함 감사 사용
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 3a7ffccadf6b415f7dd0d0871d368402332a0cd7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916746"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="a4d66-102">사서함 감사 사용</span><span class="sxs-lookup"><span data-stu-id="a4d66-102">Enable mailbox auditing</span></span>

<span data-ttu-id="a4d66-103">단일 사용자 또는 조직 전체에 대 한 사서함 감사를 사용 하도록 설정 하려면 원격 Powershell에서 다음 cmdlet은 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d66-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="a4d66-104">**단일 사용자**</span><span class="sxs-lookup"><span data-stu-id="a4d66-104">**Single User**</span></span>
  
<span data-ttu-id="a4d66-105">Set-mailbox-Identity "Jane Dow"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="a4d66-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="a4d66-106">**조직**</span><span class="sxs-lookup"><span data-stu-id="a4d66-106">**Organization**</span></span>
  
<span data-ttu-id="a4d66-107">Get-mailbox ResultSize 무제한-Filter {RecipientTypeDetails-eq "UserMailbox"} | Set-mailbox-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="a4d66-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="a4d66-108">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="a4d66-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

