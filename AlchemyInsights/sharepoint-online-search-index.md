---
title: SharePoint Online의 검색
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044049"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a>SharePoint Online의 콘텐츠 크롤링 및 인덱싱

사용자가 SharePoint Online에서 검색 내용을 찾을 수 있도록 콘텐츠를 크롤링한 후 검색 인덱스에 추가 해야 합니다. 콘텐츠는 미리 정의 된 크롤링 일정 (크롤링 일정을 변경할 수 없음)에 따라 자동으로 크롤링됩니다. 크롤러는 마지막 크롤링 이후에 변경된 콘텐츠를 선택하고 인덱스를 업데이트합니다. 콘텐츠가 크롤링되 고 인덱스가 업데이트 되도록 하려면 다음 사항에 유의 하십시오.

- [사이트 콘텐츠를 검색 가능 하도록 설정](https://docs.microsoft.com/sharepoint/make-site-content-searchable)하 여 콘텐츠를 찾을 수 있는지 확인 합니다.

- 관리 속성을 변경 하거나 크롤링 속성과 관리 속성의 매핑을 변경한 후에는 변경 내용을 검색 인덱스에 반영 하기 전에 사이트를 다시 크롤링되 야 합니다. 

    변경 내용이 실제 사이트가 아니라 검색 스키마에서 이루어지기 때문에 크롤러가 자동으로 사이트에 다시 인덱싱하지 않습니다. 

    자세한 내용은 [사이트, 라이브러리 또는 목록에 대 한 크롤링 수동 요청과 다시 인덱싱](https://docs.microsoft.com/sharepoint/crawl-site-conten)를 참조 하세요.

- 크롤링을 수동으로 요청한 후 24 시간 이상 기다렸다가 전체 다시 인덱스를 만들어 문제가 발생 했는지 확인 합니다. 

    크롤링을 시작한 후에 24 시간 이상이 통과 한 경우에는 지원 사례를 기록 하세요. 대부분의 경우에는 이미 솔루션을 사용 하 고 있습니다. 솔루션을 완료 하려면 최소한 24 시간 이상 기다려 주세요.

> [!IMPORTANT]
> 사이트, 문서 (라이브러리) 또는 목록이 삭제 되어 여전히 검색 결과에 표시 되는 경우 사용자에 게 액세스 하려고 할 때 **오류 404 파일을 찾을 수 없습니다** . 라는 오류가 표시 됩니다. 이 문제는 추가 조사를 위한 지원 사례로 기록해 야 합니다. 



