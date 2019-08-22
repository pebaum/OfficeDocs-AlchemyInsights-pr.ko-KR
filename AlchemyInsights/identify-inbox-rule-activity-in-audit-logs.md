---
title: 감사 로그의 받은 편지함 규칙 활동 식별
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539179"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>감사 로그의 받은 편지함 규칙 활동 식별

Office 365 보안 & 준수 센터에서 감사 로그 검색을 사용 하 여 받은 편지함 규칙을 만들고, 수정 하 고, 삭제할 수 있습니다.

1. [Office 365 보안 & 준수 센터](https://protection.office.com/)에 로그인 합니다.

2. **검색** > **감사 로그 검색** 페이지로 이동 합니다.

3. **시작 날짜** 및 **끝 날짜** 필드에서 날짜 범위를 선택 합니다.

4. **Exchange 사서함 활동**에서 **작업** 필드가 **disable-inboxrule 만들기/수정/사용/사용 안 함 받은 편지함 규칙**으로 설정 되어 있는지 확인 합니다.

5. **검색**을 클릭합니다.

결과에서 감사 레코드를 선택 합니다. 세부 정보 플라이 아웃에서 **추가 정보**를 클릭 합니다. 받은 편지함 규칙 설정에 대 한 정보는 **매개 변수** 필드에 표시 됩니다.

자세한 내용은 [사용자가 받은 편지함 규칙을 만들었는지 확인](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule) 을 참조 하십시오.
