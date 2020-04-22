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
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676503"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>오류 코드 5.7.23에 대 한 전자 메일 배달 문제 해결

공개적으로 사용 가능한 SPF 또는 웹의 DNS 레코드 검사기에서 도메인에 대 한 SPF DNS 레코드를 확인 합니다.

아웃 바운드 메시지가 Microsoft의 스팸으로 식별 되지 않아 [위험성이 높은 배달 풀](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages)을 통해 라우팅됩니다. 높은 위험 배달 풀의 메시지는 SPF 검사를 통과 하지 않으므로 대상 전자 메일 조직에서 허용 되지 않습니다.

문제가 계속 되 면 전자 메일을 보내려고 시도 하는 메일 호스트의 관리자에 게 문의 해야 할 수도 있습니다. 바운스 메시지에서 사용할 수 있는 자세한 외부 오류를 기록 합니다. Microsoft support가 더 이상 지원 하지 않을 수 있습니다.
