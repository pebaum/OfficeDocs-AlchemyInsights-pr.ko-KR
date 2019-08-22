---
title: 콘텐츠 검색 결과 없음
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 09cdbc3cb0465e0e0bc08872c49e283081ad3e92
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36516785"
---
# <a name="no-results-from-content-searchexports"></a>콘텐츠 검색/내보내기에서 결과 없음

콘텐츠 검색/내보내기 관련 문제는 특정 관리자가 설치 하 고 모든 관리자에 게 통신 하지는 않는 특정 준수 보안 필터로 인해 데이터를 반환 하지 않을 수 있습니다.

이 문제를 해결 하려면 다음과 같은 규정 준수 보안 필터가 있는지 확인 하십시오.
1. 보안 및 준수 센터 Powershell에 연결
2. 다음을 실행 합니다.
<br>$org = "yourdomain.com"
<br>New-compliancesecurityfilter-조직 $org