---
title: Teams 클라이언트의 작동이 중지되나요?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030682"
---
# <a name="teams-client-crashing"></a>Teams 클라이언트의 작동이 중지되나요?

Teams 클라이언트의 작동이 중단되면 다음을 시도해 보세요.

- Teams 데스크톱 앱을 사용하는 경우 [앱이 완전히 업데이트되었는지 확인합니다](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

- 모든 [Office 365 URL과 주소 범위](https://docs.microsoft.com/microsoftteams/connectivity-issues)에 액세스할 수 있는지 확인합니다.

- 관리자 계정으로 로그인하고 [서비스 상태 대시보드](https://docs.microsoft.com/office365/enterprise/view-service-health)를 확인하여 작동 중단 또는 서비스 저하가 없는지 확인합니다.

 - 마지막 단계로 Teams 클라이언트 캐시를 지울 수 있습니다.

    1.  Microsoft Teams 데스크톱 클라이언트를 완전히 종료합니다. 아이콘 트레이에서 **Teams**를 마우스 오른쪽 단추를 클릭하고 **종료**를 클릭하거나 작업 관리자를 실행하여 프로세스를 완전히 종료할 수 있습니다.

    2.  파일 탐색기로 이동한 다음 %appdata%\Microsoft\teams를 입력합니다.

    3.  이 디렉터리에서 다음과 같은 폴더를 볼 수 있습니다.

         - **Application Cache**에서 Cache로 이동한 후 캐시 위치 %appdata%\Microsoft\teams\application cache\cache에서 파일을 삭제합니다.

        - **Blob_storage**에서 %appdata%\Microsoft\teams\blob_storage의 모든 파일을 삭제합니다.

        - **Cache**에서 %appdata%\Microsoft\teams\Cache의 모든 파일을 삭제합니다.

        - **databases**에서 %appdata%\Microsoft\teams\databases의 모든 파일을 삭제합니다.

        - **GPUCache**에서 %appdata%\Microsoft\teams\GPUcache의 모든 파일을 삭제합니다.

        - **IndexedDB**에서 %appdata%\Microsoft\teams\IndexedDB의 .db 파일을 삭제합니다.

        - **Local Storage**에서 %appdata%\Microsoft\teams\Local Storage의 모든 파일을 삭제합니다.

        - 마지막으로 **tmp**에서 %appdata%\Microsoft\teams\tmp의 모든 파일을 삭제합니다.

    4. Teams 클라이언트를 다시 시작합니다.
