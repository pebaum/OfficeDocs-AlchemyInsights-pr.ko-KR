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
ms.openlocfilehash: 9f2c0273762f1a4a2b905487f461dc1d05db9209
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800442"
---
# <a name="no-results-from-content-searchexports"></a>콘텐츠 검색/내보내기에서 결과 없음

콘텐츠 검색/내보내기 관련 문제는 특정 관리자가 설치 하 고 모든 관리자에 게 통신 하지는 않는 특정 준수 보안 필터로 인해 데이터를 반환 하지 않을 수 있습니다.

이 문제를 해결 하려면 다음과 같은 규정 준수 보안 필터가 있는지 확인 하십시오.
1. 보안 및 준수 센터 Powershell에 연결
2. 다음을 실행 합니다.
<br>$org = "yourdomain.com"
<br>New-compliancesecurityfilter-조직 $org