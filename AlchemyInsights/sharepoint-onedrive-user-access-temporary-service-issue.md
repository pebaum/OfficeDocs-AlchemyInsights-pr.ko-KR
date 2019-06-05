---
title: 성능 문제-SharePoint 또는 OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719522"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint 또는 OneDrive 느림, 액세스 불가 또는 여러 사용자가 사용할 수 없음

이전에 액세스 한 여러 사용자가 OneDrive 또는 SharePoint 사이트를 사용할 수 없는 경우 일시적인 서비스 문제가 있을 수 있습니다. [서비스 상태 대시보드를 확인](https://portal.office.com/adminportal/home#/servicehealth)합니다.

## <a name="add-and-license-the-user"></a>사용자 추가 및 라이선스를 허가 합니다.

[비즈니스용 Office 365에서 사용자에 게 라이선스를 할당](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One)했는지 확인 합니다.


## <a name="assign-permissions"></a>사용 권한 할당

사용자에 게 Sharepoint 라이선스가 할당 되 고 여전히 액세스 거부 메시지를 수신 하는 경우에는 [해당 권한 수준이](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) 할당 되어 있는지 확인 하세요.

## <a name="consider-using-the-access-request-feature"></a>액세스 요청 기능 사용 고려

[액세스 요청 기능](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) 을 사용 하면 사용자가 현재 볼 수 있는 권한이 없는 콘텐츠에 대 한 액세스를 요청할 수 있습니다.

## <a name="allow-custom-script-may-cause-access-denied-issues"></a>사용자 지정 스크립트를 허용 하면 액세스 거부 문제가 발생할 수 있음

*사용자 지정 스크립트 허용* 기능이 액세스 거부를 표시할 수 있는 몇 가지 시나리오가 있습니다. 영향을 받는 기능 목록, 보안 고려 사항 및 기능을 사용 하지 않도록 설정 하는 기능 [사용자 지정 스크립트 허용 또는 금지](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)를 참조 하세요.

