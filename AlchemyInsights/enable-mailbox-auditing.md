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
# <a name="enable-mailbox-auditing"></a>사서함 감사 사용

단일 사용자 또는 전체 조직에 대해 사서함 감사를 사용 하도록 설정 하려면 원격 전원 셸에서 다음 cmdlet을 실행 해야 합니다.
  
 **단일 사용자**
  
Set-Mailbox-Id "Jane Dow"-AuditEnabled $true
  
 **조직**
  
Get-Mailbox-ResultSize 무제한-필터 {RecipientTypeDetails-eq "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[자세한 정보](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

