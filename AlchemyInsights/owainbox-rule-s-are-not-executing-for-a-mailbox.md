---
title: 1332 OWA-사서함에 대 한 받은 편지함 규칙이 실행 되 고 있지 않음
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1332
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 28b03183552e00dd2522fff51b061cc27d5032ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34762229"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>받은 편지함 규칙이 예상 대로 작동 하지 않음

다음 설정을 확인 합니다.

- 받은 편지함 규칙을 한 번에 하나씩 자동으로 사용 하 여 메시지를 리디렉션하고 전달 하거나 회신할 수 있습니다. 리디렉션 규칙 (받은 편지함 규칙 또는 전송 규칙이 라고도 하는 메일 흐름 규칙)은 최대 10 개의 전달 받는 사람을 메시지에 추가할 수 있습니다. 자세한 내용은 [저널, 전송 및 받은 편지함 규칙 제한을](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)참조 하세요.

- 받은 편지함 규칙은 대체 저널링 사서함에서 작동 하지 않습니다. 대체 저널링 사서함에 대 한 자세한 내용은 [대체 저널링 사서함](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox)을 참조 하십시오.

이러한 문제를 해결 하려면 [Kb(52829319](https://support.microsoft.com/kb/2829319)를 참조 하세요.

이전 문제가 적용 되지 않으면 Microsoft 지원으로 문제를 에스컬레이션 하기 전에 받은 편지함 규칙 진단 보고서를 실행 합니다.

1. 웹용 Outlook에서 사서함을 열고 **설정** \> **옵션** \> **구성 전자 메일** \> **받은 편지함 규칙**을 클릭 합니다.

2. 페이지 맨 아래에서 **규칙이 작동 하지 않으면 여기를 클릭 하 여 진단 보고서를 생성**합니다.
