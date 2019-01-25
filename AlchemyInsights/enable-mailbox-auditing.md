---
title: 사서함 감사 사용
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: bd94ec10f9df2e72ec6e3d8552d2eb80212a9d78
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29500288"
---
# <a name="enable-mailbox-auditing"></a>사서함 감사 사용

단일 사용자 또는 조직 전체에 대 한 사서함 감사를 사용 하도록 설정 하려면 원격 Powershell에서 다음 cmdlet은 실행 해야 합니다.
  
 **단일 사용자**
  
Set-mailbox-Identity "Jane Dow"-AuditEnabled $true
  
 **조직**
  
Get-mailbox ResultSize 무제한-Filter {RecipientTypeDetails-eq "UserMailbox"} | Set-mailbox-AuditEnabled $true
  
[자세한 정보](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

