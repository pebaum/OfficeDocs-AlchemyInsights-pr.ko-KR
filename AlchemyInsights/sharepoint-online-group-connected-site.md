---
title: SharePoint 사이트에 그룹 추가
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: f0126f7f753275e9bbf8c3a09a6af5faf9a27862
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758736"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>SharePoint Online에서 그룹 연결 된 사이트 만들기

그룹 연결 사이트를 만들거나 다시 만들 때 몇 가지 일반적인 문제가 발생 합니다.

 그룹 및 연결 된 사이트를 삭제 하 고 동일한 URL을 사용 하 여 다른 사이트를 만들려는 경우에는 이전 사이트를 영구적으로 제거 해야 합니다.

[SPO 관리 셸](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) 다운로드

 Powershell을 시작 하는 방법에 대 한 자세한 내용은 [SharePoint Online 관리 셸을 시작](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) 하기를 참조 하세요.

[Remove-spodeletedsite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet을 사용 하 여 삭제 된 사이트에서 사이트를 제거 합니다.

그룹 연결 사이트를 만들고 경고를 수신 하는 경우 별칭이 같은 다른 그룹이 이미 있으면 [관리 센터에서 Office 365](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups)의 기존 그룹을 확인 합니다. 이 문제를 해결 하려면 기존 그룹이 더 이상 필요 하지 않은 경우 삭제 하거나 다른 별칭을 할당 하 여 사이트를 만듭니다.

SharePoint에서 최신 그룹을 만들고 사용 하는 방법에는 여러 가지가 있습니다.

기존 사이트를 Office 365 그룹에 연결할 수 있습니다. 자세한 내용은 [Connect a Office 365 group Using SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface)을 참조 하십시오.

Office 365 그룹 연결 사이트를 만들려면 팀 사이트를 만들어야 합니다. 자세한 내용은 [SharePoint에서 팀 사이트 만들기](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d)를 참조 하세요.

