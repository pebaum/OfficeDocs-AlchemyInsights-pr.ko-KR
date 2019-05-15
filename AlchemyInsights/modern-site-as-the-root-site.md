---
title: 최신 사이트를 루트 사이트로
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 6166493f79379f44b1a9bbbaca6becfe624fe912
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057735"
---
# <a name="modern-site-as-root-site"></a>최신 사이트를 루트 사이트로

[대상 릴리스](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) 고객은 이제 SharePoint 테 넌 트의 기본 루트 사이트에서 최신 커뮤니케이션 사이트 환경을 사용 하도록 설정할 수 있습니다.

이 기능은 간단한 PowerShell cmdlet을 실행 하 여 활성화할 수 있습니다. PowerShell 명령을 성공적으로 실행 하면 루트 사이트에 새 통신 사이트 홈 페이지가 포함 됩니다. PowerShell cmdlet 및 기능 요구 사항에 대 한 자세한 내용은 [SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps)문서에서 확인할 수 있습니다. 

Microsoft는이를 점진적으로 롤아웃할 예정 이며, 기본적으로는 이전에는 2019 년 5 2019 월 말에 대상으로 지정 된 릴리스 고객에 게 제공 됩니다. 계속 해 서 다른 새로운 기능인 최신 기능을 보려면 [메시지 센터](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) 를 참조 하세요. 

**중요**: 최신 통신 사이트를 만들려면 클래식 루트 사이트를 삭제 하지 마십시오. 이 기능은 Microsoft에서 지원 되지 않습니다. 루트 사이트를 삭제 하면 사이트를 복원 하거나 같은 URL에 새 사이트를 만들 때까지 조직의 모든 SharePoint 사이트가 모든 사용자에 게 액세스 하지 못하게 됩니다. 
 
 