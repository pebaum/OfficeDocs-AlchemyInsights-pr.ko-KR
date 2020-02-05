---
title: SharePoint 및 OneDrive 알림 받기의 지연
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 02/04/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 0bc9f614047e06e8654a9b3ff64e87427f33139f
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/04/2020
ms.locfileid: "41771221"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="b9447-102">SharePoint 및 OneDrive 알림 받기의 지연</span><span class="sxs-lookup"><span data-stu-id="b9447-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="b9447-103">먼저 전자 메일에서 정크 또는 스팸 폴더를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="b9447-104">**여러 파일 또는 라이브러리의 모든 알림이 지연 된**경우 [서비스 상태 대시보드](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) 를 방문 하 여 SharePoint 또는 Exchange에서 발생할 수 있는 모든 권고/사고를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="b9447-105">이 문제는 Exchange를 통한 전자 메일의 SharePoint 알림 기능 또는 지연에 있을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="b9447-106">또한 다른 전자 메일이 배달 되는지 여부도 확인 합니다 (그렇지 않은 경우 Exchange 지연에 문제가 있을 수 있음).</span><span class="sxs-lookup"><span data-stu-id="b9447-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="b9447-107">**특정 파일이 나 라이브러리의 개별 알림이 배달 되지**않으면 삭제 하 고 다시 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="b9447-108">경고를 다시 만들려면 [SharePoint 알림 관리, 보기 또는 삭제](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="b9447-108">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="b9447-109">메일 그룹에 알림을 보낼 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="b9447-110">보안 및 O365 그룹만 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="b9447-111">경고 전자 메일 템플릿은 사용자 지정할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="b9447-112">이러한 사항을 구현 하려면 Microsoft Flow 또는 SharePoint Designer 워크플로를 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9447-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
