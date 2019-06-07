---
title: SharePoint Online 권한 수준
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760698"
---
# <a name="sharepoint-designer-connection-issues"></a>SharePoint Designer 연결 문제 

SharePoint Designer에 SharePoint 사이트에 대 한 연결 문제가 발생 한 경우 다음 일반 솔루션을 시도해 보세요.

1 단계: SharePoint Designer가 업데이트 되었는지 확인 합니다.

- [SharePoint Designer 2013](https://www.microsoft.com/download/details.aspx?id=35491)

- [SharePoint Designer SP1 (서비스 팩 1)](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [SharePoint Designer 2013에 대 한 업데이트 (KB3114721)](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

2 단계: 로컬 캐시 파일 지우기

- SharePoint Designer 2013을 닫습니다.

- 로컬 컴퓨터에서 다음 폴더로 이동 하 여 캐시 된 파일을 제거 합니다.

- 시작, 실행을 차례로 클릭 하 고 아래의 각 위치에서 찾은 모든 파일을 삭제 합니다.

%APPDATA%\Microsoft\Web Server Extensions\Cache%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

SharePoint Designer 2013를 열고 계정을 다시 입력 하 여 작동 하는지 확인 합니다.

3 단계: [Windows 장치에서 Office 2013에 대 한 최신 인증을 사용 하도록 설정](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)

4 단계: 관리자는 SharePoint Designer 연결을 허용 하는 사용자 지정 스크립트를 허용 해야 합니다.

자세한 단계는 [허용 또는 금지 사용자 지정 스크립트](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)를 참조 하십시오.


