---
title: 클래식 SharePoint 감사 로그 보고서
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: be95034bea3c58a4fde96cfb0f9ba525e810758e
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/05/2019
ms.locfileid: "37992624"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="d6f3c-102">SharePoint 및 OneDrive 감사 로그</span><span class="sxs-lookup"><span data-stu-id="d6f3c-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="d6f3c-103">SharePoint 클래식 감사 로그</span><span class="sxs-lookup"><span data-stu-id="d6f3c-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="d6f3c-104">SPO 레거시 감사가 UAL (통합 감사 로그)로 마이그레이션 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="d6f3c-105">이제 모든 SPO 레거시 감사 보고서가 UAL를 통해 켜 지 며 레거시 감사 신호가 UAL로 마이그레이션 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="d6f3c-106">주요 변경 사항:</span><span class="sxs-lookup"><span data-stu-id="d6f3c-106">Key changes:</span></span>

* <span data-ttu-id="d6f3c-107">자르기는 기능으로 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="d6f3c-108">감사할 특정 이벤트 선택이 가능 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="d6f3c-109">기본적으로 사용할 수 있는 감사 이벤트의 전체 목록을 보려면 [이 문서](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) 를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-109">Refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="d6f3c-110">**사용자 지정 된 보고서** 에서 **위치** 옵션을 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="d6f3c-111">**문서 열기 또는 다운로드** 옵션은 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="d6f3c-112">사이트 모음에 대 한 감사 설정 구성</span><span class="sxs-lookup"><span data-stu-id="d6f3c-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="d6f3c-113">SharePoint 및 OneDrive 최신 통합 감사 로그 (규정 준수)</span><span class="sxs-lookup"><span data-stu-id="d6f3c-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="d6f3c-114">통합 감사 로깅 설정/해제</span><span class="sxs-lookup"><span data-stu-id="d6f3c-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="d6f3c-115">SharePoint 또는 OneDrive 내에 추가 구성은 필요 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="d6f3c-116">감사 로깅 검색을 사용 하 여 파일 (s), 폴더, 사용자의 사용 권한 작업을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="d6f3c-117">파일 및 페이지 활동</span><span class="sxs-lookup"><span data-stu-id="d6f3c-117">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="d6f3c-118">폴더 활동</span><span class="sxs-lookup"><span data-stu-id="d6f3c-118">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="d6f3c-119">공유 및 액세스 요청 활동</span><span class="sxs-lookup"><span data-stu-id="d6f3c-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="d6f3c-120">동기화 작업</span><span class="sxs-lookup"><span data-stu-id="d6f3c-120">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="d6f3c-121">사이트 관리 작업</span><span class="sxs-lookup"><span data-stu-id="d6f3c-121">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="d6f3c-122">이러한 이벤트를 검색 하는 방법에 대 한 자세한 내용은 [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="d6f3c-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
