---
title: 'filename이 가장 동일 [규칙 #-설명]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 01d8b03209e734f1218de61d964524b1b9e1d044
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29939303"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>필요한 연금술 헤더 H1, H2의 작동 하지 않습니다.
모범 사례 및 연금술 제작에 대 한 지침:

1. **폴더에서 연금술 인 사이트를 중첩 하지 마십시오.**-이 url 구조의 연결이 끊어집니다. 수정 하는이를 검토 하 고 있습니다.
1. **AlchemyInsights** 폴더의 파일의 파일 이름에서 규칙 ID와 [연금술 파트너 포털](https://alchemyportal.azurewebsites.net) 에서 규칙 이름이 있어야 합니다.
    1. 예: ***976-How-to-enable-litigation-hold***
1. 서식 파일에으로이 파일의 위쪽에 메타 데이터를 사용 합니다. 다른 nothing이 필요 합니다.
1. [연금술 파트너 포털](https://alchemyportal.azurewebsites.net)섹션으로 이동 **고객 견해 제목:** 및는 정보에 대 한 H1 제목에 대 한 사용 가리키는 시작 하기만 합니다. 
    > [!NOTE]
    > 연금술 인 사이트는 단일 H1만 맨 위쪽에 또는 있어야 프로덕션 환경에서 끊어집니다. 그렇게 사용 **굵게** 또는 다른 규칙을 별도 섹션을 나타내기 위해 H2s 렌더링 하지 않습니다.
1. 다음으로, 연금술 규칙 페이지의 고객 인 사이트 섹션에서 초안 자료를 사용 하 여 본문 텍스트를 입력
    1. 글머리 기호 목록은 세밀 하 게 됩니다.
    1. 너무 번호 매기기 목록
    1. **굵게** 및 *기울임꼴* a-ok 됩니다.
    1. 링크는 항상 있어야 하거나 **"웹에 대 한 링크" 외부 /** OR **UI 요소를 자세히 링크**, 하지 내부 링크입니다.

및이 이미 실제로 좀더 너무 깁니다. 모범 사례는 약 400 자--

콘텐츠를 수행할 준비가 되 면 라이브 분기를 가져와 합니다. 그런 다음, [연금술 파트너 포털](https://alchemyportal.azurewebsites.net) 에 이동 하 고 url 필드에 파일 이름을 입력 합니다. 필요한 정보를 검토 하 고 게시 "yes" 라고 표시 되어있는지 확인 하 고 업데이트 규칙을 클릭 합니다. **(이 보이는지 곧 출시-포털의 새 버전에서 저렇게.)** 
 ![url 필드](media/for-content-team.PNG)

