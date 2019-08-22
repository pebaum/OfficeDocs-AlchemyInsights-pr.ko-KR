---
title: SharePoint 경고 알림이 배달 되지 않음
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: f389785fcd1029ae5a47e07c723874f9f214109d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36504469"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="c67f2-102">SharePoint 경고 알림이 배달 되지 않음</span><span class="sxs-lookup"><span data-stu-id="c67f2-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="c67f2-103">가끔씩 경고가 발생할 수 있으므로 전자 메일에서 정크 폴더를 확인 하세요.</span><span class="sxs-lookup"><span data-stu-id="c67f2-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="c67f2-104">**모든 경고가 배달 되지** 않거나 특정 파일이 나 라이브러리의 **개별 알림이** 배달 되지 않는 경우를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="c67f2-105">**개별 알림이 배달 되지 않음**: 특정 파일 또는 라이브러리의 개별 경고가 배달 되지 않으면 삭제 하 고 다시 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="c67f2-106">경고를 다시 만들려면 [SharePoint 알림 관리, 보기 또는 삭제](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c67f2-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) to recreate the alert.</span></span>
- <span data-ttu-id="c67f2-107">**모든 경고가 배달 되지 않음**: 여러 파일 또는 라이브러리의 모든 경고가 배달 되지 않으면 [서비스 상태 대시보드](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) 를 방문 하 여 SharePoint 또는 Exchange에서 발생할 수 있는 모든 권고/사고를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="c67f2-108">이 문제는 Exchange를 통한 전자 메일의 SharePoint 알림 기능 또는 지연으로 인해 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="c67f2-109">또한 다른 전자 메일이 배달 되는지 여부를 확인 하는 것이 중요 하 고, 그렇지 않은 경우 Exchange 지연으로 인 한 문제일 가능성이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="c67f2-110">경고에 대 한 FAQ:</span><span class="sxs-lookup"><span data-stu-id="c67f2-110">FAQ on alerts:</span></span>

- <span data-ttu-id="c67f2-111">메일 그룹에 알림을 보낼 수는 없으므로 보안 및 O365 그룹만 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="c67f2-112">경고 전자 메일 템플릿은 사용자 지정할 수 없습니다. 이러한 사항을 구현 하려면 Microsoft FLOW 또는 SharePoint Designer 워크플로를 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="c67f2-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

<span data-ttu-id="c67f2-113">추가 정보:</span><span class="sxs-lookup"><span data-stu-id="c67f2-113">More Information:</span></span>

- <span data-ttu-id="c67f2-114">**알림 설정**: 알림 설정에 대 한 자세한 내용은 [SharePoint에서 파일 또는 폴더가 변경 될 때 알림을 받으려면 알림 만들기](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c67f2-114">**Alert setup**: For more information about setting up alerts, see [Create an alert to get notified when a file or folder changes in SharePoint](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span></span>
- <span data-ttu-id="c67f2-115">**경고 문제 해결**: 경고 문제 해결에 대 한 자세한 내용은 [사용자가 SharePoint Online 알림 알림을 받지 않도록](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications)합니다 .를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c67f2-115">**Troubleshoot alerts**: For more information about troubleshooting alerts, see [Users don't receive SharePoint Online alert notifications](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications).</span></span>
- <span data-ttu-id="c67f2-116">**Advanced O365 준수 경고 정책**: 이러한 경고를 설정 하는 방법에 대 한 자세한 내용은 [준수 경고 정책을](https://docs.microsoft.com/office365/securitycompliance/alert-policies)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c67f2-116">**Advanced O365 Compliance Alert Policies**: For more information about setting up these alerts, see [Compliance Alert Policies](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span></span>
- <span data-ttu-id="c67f2-117">**SharePoint 및 OneDrive 감사 로그**: 이러한 이벤트를 검색 하는 방법에 대 한 자세한 내용은 [Search the Audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c67f2-117">**SharePoint and OneDrive Audit Logs**: For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
- <span data-ttu-id="c67f2-118">**Advanced Threat Protection에서 보내는 경고**: [SharePoint 및 OneDrive에 대 한 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c67f2-118">**Alerts sent by Advanced Threat Protection**: See [ATP for SharePoint and OneDrive](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
- <span data-ttu-id="c67f2-119">**데이터 손실 방지 정책에 의해 전송 된 경고**: [DLP 정책에 대 한 전자 메일 알림을](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c67f2-119">**Alerts sent by Data Loss Prevention polices**: See [Email notifications for DLP policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

## <a name="related-topics"></a><span data-ttu-id="c67f2-120">관련 주제</span><span class="sxs-lookup"><span data-stu-id="c67f2-120">Related Topics</span></span>

<span data-ttu-id="c67f2-121">SharePoint Online에서 Microsoft Flow를 시도 하 고 싶으십니까?</span><span class="sxs-lookup"><span data-stu-id="c67f2-121">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="c67f2-122">흐름 만들기</span><span class="sxs-lookup"><span data-stu-id="c67f2-122">Create Flow</span></span>](https://support.office.com/article/create-a-flow-for-a-list-or-library-in-sharepoint-online-or-onedrive-for-business-a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="c67f2-123">SharePoint 및 흐름</span><span class="sxs-lookup"><span data-stu-id="c67f2-123">SharePoint and Flow</span></span>](https://flow.microsoft.com/en-us/blog/sharepoint-and-flow/)
