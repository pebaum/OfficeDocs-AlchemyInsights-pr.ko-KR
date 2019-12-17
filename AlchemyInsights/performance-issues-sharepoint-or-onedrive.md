---
title: 성능 문제-SharePoint 또는 OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068414"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>여러 사용자가 SharePoint 또는 OneDrive에 느리거나, 액세스 하지 않거나, 사용할 수 없음

SharePoint 또는 OneDrive는 다음과 같은 몇 가지 이유로 인해 느리거나, 액세스 불가능 하거나, 사용할 수 없거나 서비스를 사용할 수 없거나 503 오류가 표시 될 수도 있습니다.
  
- SharePoint 또는 OneDrive 사이트가 여러 사용자에 대해 느리거나 지연 되는 경우 사용자가 SharePoint 사이트 또는 OneDrive 콘텐츠에 액세스할 때 일시적으로 지연 되거나 탐색 오류가 발생 하는 일시적인 서비스 문제가 있을 수 있습니다. [서비스 상태 대시보드](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) 를 통해 조직에 영향을 준 것이 있는지 확인 합니다.
  
- SharePoint 또는 OneDrive 사이트로 이동 하려고 하면 사용자에 게 *503 서버가 통화 중* 이라는 오류가 표시 될 수 있습니다. 이 오류는 SharePoint 서비스 내의 제한으로 인해 발생할 수 있습니다. SharePoint Online에서는 제한 기능을 사용 하 여 SharePoint Online 서비스의 최적의 성능과 안정성을 유지 관리 합니다. 제한은 리소스를 과도 하 게 사용 하지 못하도록 사용자 작업 수 또는 스크립트 또는 코드에의 한 동시 통화를 제한 합니다. 제한에 대 한 자세한 내용은 [SharePoint Online에서 제한 또는 차단 되지 않도록](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)합니다 .를 참조 하세요.

- **클래식** 또는 **최신** SharePoint 사이트나 페이지로 인 한 성능이 저하 되는 경우 [페이지 진단 도구](https://aka.ms/perftool) 를 활용 하 여 페이지를 분석 합니다.
  
- 여전히 일반적인 성능 저하가 발생 하는 경우이 문서 아래쪽의 리소스를 검토 하세요. [SharePoint Online의 성능 조정 소개](https://go.microsoft.com/fwlink/?linkid=2024334)
  