---
title: SharePoint 또는 OneDrive에서 항목을 삭제할 수 없음
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057736"
---
# <a name="unable-to-delete-items"></a>항목을 삭제할 수 없음

항목을 삭제 하는 데 문제가 있나요?

- 항상 항목을 삭제 하거나 [사이트 모음 관리자](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) 가 항목을 제거할 수 있는 [적절 한 권한이](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) 있는지 확인 합니다.

- 해당 항목에 대 한 [보존 정책](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) 설정이 없는지 확인 합니다.

- 항목이 다른 사용자에 게 [체크 아웃](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) 되지 않았는지 확인 합니다.

- 마지막으로 관리자는 stubborn 항목 강제 삭제와 같은 복잡 한 관리 작업을 수행 하는 데 사용할 수 있는 PowerShell 명령 라이브러리가 포함 된 [SharePoint 패턴 및 사례](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP)를 사용할 수 있습니다. 
- [PNP 파일 제거](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [PNP 폴더 제거](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [PNP 목록 항목 제거](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [PNP 목록 제거](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [PNP 필드 제거 (열)](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)