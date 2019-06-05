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
ms.openlocfilehash: 7451cfe957545537298f57feb5b47bd6d43cddbf
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716897"
---
# <a name="sharepoint-designer-connection-issues"></a>SharePoint Designer 연결 문제 

<p>SharePoint Designer에 SharePoint 사이트에 대 한 연결 문제가 발생 한 경우 다음 일반 솔루션을 시도해 보세요.</p> <p><strong>1 단계:</strong> <strong>SharePoint Designer가 업데이트&nbsp; 되었는지 확인</strong></p> <ul> <li><a href="https://www.microsoft.com/en-us/download/details.aspx?id=35491">SharePoint Designer 2013</a></li> <li><a href="https://support.microsoft.com/en-us/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1">SharePoint Designer SP1 (서비스 팩 1)</a></li> <li><a href="https://support.microsoft.com/en-us/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721">SharePoint Designer 2013에 대 한 업데이트 (KB3114721)</a></li> </ul> <p><strong>2 단계:</strong> <strong>로컬 캐시 파일 지우기</strong>&nbsp;</p> <ol> <li style="font-weight: 400;">SharePoint Designer 2013을 닫습니다.&nbsp;</li> <li style="font-weight: 400;">로컬 컴퓨터에서 다음 폴더로 이동 하 여 캐시 된 파일을 제거 합니다.&nbsp;</li> <li style="font-weight: 400;"><strong>시작-&gt; 실행</strong> 을 클릭 하 고 각 위치 아래에서 찾은 모든 파일을 삭제 합니다.&nbsp;<br /><br />%APPDATA%\Microsoft\Web 서버 Extensions\Cache<br />%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache<br />%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</li> <li style="font-weight: 400;">SharePoint Designer 2013를 열고 계정을 다시 입력 하 여 작동 하는지 확인 합니다.</li> </ol> <p><strong>3 단계:</strong> <a href="https://docs.microsoft.com/en-us/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=%252fen-us%252farticle%252fEnable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&amp;view=o365-worldwide"> <strong>Windows 장치에서 Office 2013에 대 한 최신 인증을 사용 하도록 설정</strong></a>&nbsp;</p> <p><strong>4 단계:</strong> <strong>관리자는 SharePoint Designer 연결을 허용 하는 사용자 지정 스크립트를 허용 해야</strong>합니다.</p> <p>자세한 단계는 <a href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">허용 또는 금지 사용자 지정 스크립트</a>를 참조 하십시오.&nbsp;</p>


