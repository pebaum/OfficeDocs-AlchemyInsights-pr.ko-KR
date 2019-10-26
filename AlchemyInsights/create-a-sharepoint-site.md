---
title: SharePoint 사이트 만들기
ms.author: efrene
author: efrene
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 30c51d84005534cc1de9e8b8136da1a07be57b73
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36738203"
---
# <a name="create-a-sharepoint-site"></a>SharePoint 사이트 만들기

SharePoint 사이트 만들기에 대 한 자세한 내용은 다음 항목을 참조 하십시오.
- [새 SharePoint 관리 센터에서 사이트 관리](https://docs.microsoft.com/sharepoint/manage-site-creation): Office 365 그룹을 포함 하지 않는 팀 사이트 또는 클래식 사이트를 만드는 방법을 포함 하 여 사이트 만들기 옵션에 대해 알아봅니다.
- [SharePoint에서 팀 사이트 만들기](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): 팀 사이트를 만드는 방법을 알아봅니다.
- [SharePoint Online에서 커뮤니케이션 사이트 만들기](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): 통신 사이트를 만드는 방법을 알아봅니다.
- [새 SharePoint 관리 센터에서 사이트 관리](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Office 365 그룹이 포함 되지 않은 클래식 사이트 또는 팀 사이트를 만드는 방법에 대해 알아봅니다.


  
> [! 정보
> - 기존 사이트와 동일한 URL을 사용 하 여 사이트를 만들 수는 없습니다. 사이트를 삭제 하 고 해당 URL을 다시 사용 하려는 **경우 삭제 된 사이트 아래에**해당 사이트가 계속 남아 있을 수 있습니다. 삭제 된 사이트를 관리 하려면 [사이트 삭제](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site)를 참조 하세요. Powershell을 사용 하 여 사이트를 완전히 제거 하려면 [제거-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet 예제를 참조 하세요.
> - 일부 사용자가 사이트를 만들지 못할 수 있습니다. [SharePoint Online에서 사이트 만들기 관리를](https://docs.microsoft.com/sharepoint/manage-site-creation)참조 하세요.
> - 사이트가 예상 보다 오래 **생성** 되는 것 처럼 표시 될 수 있습니다. 이 문제가 처음 발생 한 것으로 24 시간 이상 경과 된 경우 지원 티켓을 기록 하세요. 대부분의 경우에는 이미 솔루션을 사용 하 고 있습니다. 솔루션을 완료 하려면 최소한 24 시간 이상 기다려 주세요.
> - Office 365 그룹을 포함 하지 않는 새 팀 사이트를 만들어야 하는 경우 


