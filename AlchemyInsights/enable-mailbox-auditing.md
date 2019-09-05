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
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 73517f46935a67a4a8a3e4770090ac897fe67979
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736259"
---
# <a name="enable-mailbox-auditing"></a>사서함 감사 사용

단일 사용자 또는 전체 조직에 대해 사서함 감사를 사용 하도록 설정 하려면 원격 전원 셸에서 다음 cmdlet을 실행 해야 합니다.
  
 **단일 사용자**
  
Set-Mailbox-Id "Jane Dow"-AuditEnabled $true
  
 **조직**
  
Get-Mailbox-ResultSize 무제한-필터 {RecipientTypeDetails-eq "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[자세한 정보](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

