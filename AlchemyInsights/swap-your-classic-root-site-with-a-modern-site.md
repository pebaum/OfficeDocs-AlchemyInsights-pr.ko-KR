---
title: 기본 루트 사이트를 최신 사이트로 바꾸기
ms.author: pebaum
author: pebaum
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: fe1f0f662c49de2bd0b5b997697c98309cb7983f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40042933"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>기본 루트 사이트를 최신 사이트로 바꾸기

환경을 4 월 2019 이전에 설정한 경우 Microsoft PowerShell을 사용 하 여 루트 사이트를 최신 사이트로 변경할 수 있습니다.

- 루트 사이트로 사용 하려는 다른 사이트가 있는 경우 루트 사이트를 해당 사이트로 바꿀 수 있습니다 [(교체)](https://docs.microsoft.com/sharepoint/modern-root-site) . 
    - [SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) 를 사용 하 여 원본 사이트를 보관 하는 동안 사이트의 위치를 다른 사이트와 교환 합니다. 두 팀 사이트 (그룹에 연결 되지 않음)와 통신 사이트에서 사용할 수 있습니다. 

- 사이트의 콘텐츠를 계속 사용할 수 있지만 기존 사이트를 통신 사이트로 변환 하는 데 도움이 되는 추가 기능이 곧 소개 될 예정입니다. 
>[!Important]
>이러한 기능을 단계적으로 롤아웃할 수 있습니다. 계속 해 서 Office 365 메시지 센터에서 업데이트를 확인 합니다. 

## <a name="known-issues-with-swapping-sites"></a>사이트 교체에 대 한 알려진 문제

- 대상 사이트에서 짧은 시간 동안 "찾을 수 없음" (HTTP 404) 오류가 반환 될 수 있습니다.
- 콘텐츠를 다시 크롤링 하 여 검색 인덱스를 업데이트 해야 합니다. 수동 단계가 필요 하지 않음-이 작업은 자동으로 수행 됩니다.
- "정적" 링크 (예: 파일 동기화 및 OneNote 파일)에 종속 된 모든 것을 수동으로 수정 해야 합니다.
- 원본 사이트가 조직 뉴스 사이트인 경우 URL을 업데이트 합니다.모든 조직 뉴스 사이트의 목록을 가져옵니다.
- Project Server 사이트가 여전히 올바르게 연결 되어 있는지 확인 하기 위해 프로젝트 서버 사이트의 유효성을 검사 해야 할 수 있습니다.





