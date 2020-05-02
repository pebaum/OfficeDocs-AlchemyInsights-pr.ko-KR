---
title: 개인 채널
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001223"
- "3205"
ms.openlocfilehash: be518df0d40123c1f0da6596bd6e2e91a0c2c8fa
ms.sourcegitcommit: 057d87c9d866fa1371d02350420d13774545c028
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/02/2020
ms.locfileid: "44005444"
---
# <a name="private-channels-in-microsoft-teams"></a>Microsoft 팀의 개인 채널

개인 채널은 Microsoft 팀의 새로운 기능입니다. 개인 채널은 표준 채널에서 변환 하거나 그 반대로 변환할 수 없습니다.

개인 채널 [만들기, 구성원 자격](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) 및 [개인 채널 SharePoint 사이트](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites)에 대 한 정보 등 개인 채널에 대 한 자세한 내용은 [Microsoft 팀의 개인 채널](https://docs.microsoft.com/MicrosoftTeams/private-channels)을 참조 하십시오. 

**참고:** 개인 채널 메시지 보존에 대 한 구성은 아직 지원 되지 않으므로 보존 정책이 사용 하도록 설정 된 테 넌 트에는 기본적으로 개인 채널이 사용 하도록 설정 되어 있지 않습니다. 팀 관리 센터에서 개인 채널을 사용 하도록 설정할 수 있습니다. 또한 개인 채널 메시지를 보존 하는 것이 지원 되지 않는 경우에도 개인 채널에서 공유 되는 파일을 보존 하는 것이 지원 됩니다.

**새 팀 소유자가 필요 하세요?**

개인 채널 소유자가 나가면 팀 Powershell을 통해 새 팀 소유자를 추가할 수 있습니다.


- [여기](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) 로 이동 하 여 팀 Powershell을 설치 하세요.

필요한 cmdlet은 다음과 같습니다.

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

팀 Powershell에 대 한 자세한 내용은 [팀 Powershell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview)를 참조 하세요.
