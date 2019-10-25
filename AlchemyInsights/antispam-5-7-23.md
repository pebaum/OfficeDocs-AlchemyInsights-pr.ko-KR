---
title: 스팸 방지-5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682196"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>오류 코드 5.7.23에 대 한 전자 메일 배달 문제 해결

공개적으로 사용 가능한 SPF 또는 웹의 DNS 레코드 검사기에서 도메인에 대 한 SPF DNS 레코드를 확인 합니다.

아웃 바운드 메시지가 Office 365에서 스팸으로 식별 되지 않았고 [높은 위험 배달 풀](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages)을 통해 라우팅되는 지 확인 합니다. 높은 위험 배달 풀의 메시지는 SPF 검사를 통과 하지 않으므로 대상 전자 메일 조직에서 허용 되지 않습니다.

문제가 계속 되 면 전자 메일을 보내려고 시도 하는 메일 호스트의 관리자에 게 문의 해야 할 수도 있습니다. 바운스 메시지에서 사용할 수 있는 자세한 외부 오류를 기록 합니다.  Office 365 지원에서 더 이상 도움을 받을 수 없습니다.