---
title: SharePoint 경고 알림이 배달 되지 않음
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: a422805d11a128909e1be7bf5d08b24efc132e23
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742053"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a>SharePoint 경고 알림이 배달 되지 않음

가끔씩 경고가 발생할 수 있으므로 전자 메일에서 정크 폴더를 확인 하세요.

**모든 경고가 배달 되지** 않거나 특정 파일이 나 라이브러리의 **개별 알림이** 배달 되지 않는 경우를 확인 합니다.

- **개별 알림이 배달 되지 않음**: 특정 파일 또는 라이브러리의 개별 경고가 배달 되지 않으면 삭제 하 고 다시 만들 수 있습니다. 경고를 다시 만들려면 [SharePoint 알림 관리, 보기 또는 삭제](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) 를 참조 하세요.
- **모든 경고가 배달 되지 않음**: 여러 파일 또는 라이브러리의 모든 경고가 배달 되지 않으면 [서비스 상태 대시보드](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) 를 방문 하 여 SharePoint 또는 Exchange에서 발생할 수 있는 모든 권고/사고를 확인 합니다. 이 문제는 Exchange를 통한 전자 메일의 SharePoint 알림 기능 또는 지연으로 인해 발생할 수 있습니다. 또한 다른 전자 메일이 배달 되는지 여부를 확인 하는 것이 중요 하 고, 그렇지 않은 경우 Exchange 지연으로 인 한 문제일 가능성이 높습니다.

경고에 대 한 FAQ:

- 메일 그룹에 알림을 보낼 수는 없으므로 보안 및 O365 그룹만 지원 됩니다.
- 경고 전자 메일 템플릿은 사용자 지정할 수 없습니다. 이러한 사항을 구현 하려면 Microsoft FLOW 또는 SharePoint Designer 워크플로를 사용 해야 합니다.

추가 정보:

- **알림 설정**: 알림 설정에 대 한 자세한 내용은 [SharePoint에서 파일 또는 폴더가 변경 될 때 알림을 받으려면 알림 만들기](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918)를 참조 하십시오.
- **경고 문제 해결**: 경고 문제 해결에 대 한 자세한 내용은 [사용자가 SharePoint Online 알림 알림을 받지 않도록](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications)합니다 .를 참조 하십시오.
- **Advanced O365 준수 경고 정책**: 이러한 경고를 설정 하는 방법에 대 한 자세한 내용은 [준수 경고 정책을](https://docs.microsoft.com/office365/securitycompliance/alert-policies)참조 하세요.
- **SharePoint 및 OneDrive 감사 로그**: 이러한 이벤트를 검색 하는 방법에 대 한 자세한 내용은 [Search the Audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log)을 참조 하십시오.
- **Advanced Threat Protection에서 보내는 경고**: [SharePoint 및 OneDrive에 대 한 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)를 참조 하세요.
- **데이터 손실 방지 정책에 의해 전송 된 경고**: [DLP 정책에 대 한 전자 메일 알림을](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)참조 하세요.

## <a name="related-topics"></a>관련 항목

SharePoint Online에서 Microsoft Flow를 시도 하 고 싶으십니까?

- [흐름 만들기](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [SharePoint 및 흐름](https://flow.microsoft.com//blog/sharepoint-and-flow/)
