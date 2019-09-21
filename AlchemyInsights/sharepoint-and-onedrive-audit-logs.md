---
title: 클래식 SharePoint 감사 로그 보고서
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068029"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>SharePoint 및 OneDrive 감사 로그

**SharePoint 및 OneDrive 최신 통합 감사 로그 (규정 준수)**

- [통합 감사 로깅 설정/해제](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

SharePoint 또는 OneDrive 내에 추가 구성은 필요 하지 않습니다.

- 감사 로깅 검색을 사용 하 여 파일 (s), 폴더, 사용자의 사용 권한 작업을 확인 합니다.

    - [파일 및 페이지 활동](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [폴더 활동](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [공유 및 액세스 요청 활동](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [동기화 작업](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [사이트 관리 작업](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- 이러한 이벤트를 검색 하는 방법에 대 한 자세한 내용은 [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log)을 참조 하십시오.

**SharePoint 클래식 감사 로그**

SPO 레거시 감사를 UAL (통합 감사 로그)로 마이그레이션 했습니다. 즉, 모든 SPO 레거시 감사 보고서는 이제 UAL를 통해 켜지 며 레거시 감사 신호가 UAL로 마이그레이션 되었음을 의미 합니다.

주요 변경 사항:

- 기능을 사용할 수 없기 때문에 트리밍
- 감사에 대해 특정 이벤트를 선택 하는 섹션을 사용할 수 없습니다. 기본적으로 사용할 수 있는 감사 이벤트의 전체 목록은 [이 문서](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) 를 참조 하세요.
- **사용자 지정 된 보고서** 의 "위치" 옵션을 사용할 수 없습니다. 
- "문서 열기 또는 다운로드" 이벤트를 사용할 수 없습니다. 

