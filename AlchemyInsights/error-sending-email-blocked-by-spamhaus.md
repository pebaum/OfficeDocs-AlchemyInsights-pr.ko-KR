---
title: SpamHaus에서 차단 된 전자 메일을 보내는 동안 오류 발생
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 39213f6f1b96c2bef9ea071f43c38766debf64d1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527142"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>전자 메일 보내기 오류: Spamhaus을 사용 하 여 클라이언트 호스트가 차단 됨

메시지를 보낸 IP 주소가 [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245)에서 소유한 차단 목록에 있습니다. Spamhaus에 의해 차단 되는 이유에는 손상 된 계정, 공용 IP 주소를 공유 하는 손상 된 컴퓨터 및 ISP (인터넷 서비스 공급자) 정책이 포함 되어 있습니다. 가능한 수정은 다음과 같습니다.
  
- 원본 전자 메일 서버를 제어 하는 Office 365에 대 한 차단 되는 인바운드 메시지의 경우 원인을 확인 하 고 Spamhaus 웹 사이트에서 해당 블록을 제거 해야 합니다.

- 원본 IP 주소가 다른 사람에 게 속하는 차단 된 인바운드 메시지를 Office 365에 저장 하려면 주소 소유자가 Spamhaus 웹 사이트에서 해당 블록을 제거 해야 합니다. IP 주소가 정책 차단 목록 (PBL)에 있는 경우 소유자는 다른 고정 IP 주소를 할당 하거나 PBL에서 주소를 제거할 수 있습니다.

- Office 365 도메인에서 차단 된 아웃 바운드 메시지의 경우 메시지가 타사 서비스를 통해 라우팅되는 경우이 오류를 수신할 수 있습니다. WHOIS 조회 도구를 사용 하 여 차단 된 IP 주소 소유자를 찾을 수 있습니다.
