---
title: 1491-search-not-returning-expected-results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964905"
---
# <a name="content-search-not-returning-expected-results"></a>예상된 결과 반환 하지 콘텐츠 검색

Office 365 보안 & 준수 센터에서에서 콘텐츠 검색을 실행할 때 예기치 않은 검색 결과 나타날 수 있습니다. 검색 결과 영향을 줄 수 있는 다음과 같은 사항을 고려해 야 합니다.

- **콘텐츠 위치 및 검색 조건**: 적절 한 콘텐츠 위치 선택 하 고 검색 조건에 있는지 확인 합니다. (여러 위치)와 대규모 검색을 실행 한 경우에 여러 검색으로 분할 하는 것이 좋습니다.

- **부분적으로 인덱싱된 항목**: 예상된 검색 결과에 포함 된 사서함에서 [부분적으로 인덱싱된 항목](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) 입니다. 그러나 OneDrive 및 SharePoint 사이트에서 부분적으로 인덱싱된 항목 검색 예측에 포함 되지 않습니다.

- **검색 오류**: CS008-009 및 CS012-002와 같은 오류 코드와 함께 검색 오류 많은 수의 사서함 (100000 사서함의 경우)를 검색할 때 발생할 수 있습니다). 이 경우 오류가 발생 한 콘텐츠 위치에 대해서만 검색을 다시 시도 하십시오. 자세한 내용은 [이 문서](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) 를 참조 하십시오.
