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
ms.openlocfilehash: 81041685cf383a231a9a9739d6daffd6039b4602
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32403753"
---
# <a name="enable-mailbox-auditing"></a>사서함 감사 사용

단일 사용자 또는 전체 조직에 대해 사서함 감사를 사용 하도록 설정 하려면 원격 전원 셸에서 다음 cmdlet을 실행 해야 합니다.
  
 **단일 사용자**
  
Set-Mailbox-id "Jane Dow"-auditenabled $true
  
 **조직**
  
Get-Mailbox-resultsize 무제한-필터 {RecipientTypeDetails-eq "usermailbox"} | Set-Mailbox-auditenabled $true
  
[자세한 정보](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

