---
title: Dynamics 365-Dynamics 365 통합 인터페이스에 잘못 된 대시보드가 표시 됨
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/15/2019
ms.locfileid: "36528557"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="f80d0-102">Dynamics 365 통합 인터페이스에 잘못 된 대시보드가 표시 됨</span><span class="sxs-lookup"><span data-stu-id="f80d0-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="f80d0-103">예상과 다른 대시보드가 표시 되는 몇 가지 이유는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="f80d0-104">사용자가 사용자 기본 대시보드를 설정 했습니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="f80d0-105">**기본적으로 설정** 단추가 대시보드 명령 모음에 표시 되지 않는 경우 일반적으로 사용자 기본 대시보드가 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="f80d0-106">사용자의 기본 대시보드가 현재 앱에 없는 경우에도 사용자 기본 대시보드는 다른 모든 기본 대시보드를 재정의 합니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="f80d0-107">다음 해결 방법을 사용 하 여 기본 대시보드를 설정 해제할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="f80d0-108">새 개인 대시보드를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="f80d0-109">새 대시보드를 사용자 기본값으로 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="f80d0-110">대시보드를 삭제 합니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="f80d0-111">대시보드는 사이트 맵에서 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="f80d0-112">대시보드를 선택 하 고 ' 시스템 사용자 지정 ' 아래의 ' 기본값으로 설정 '을 선택 하 여 조직 기본 대시보드를 설정 했을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="f80d0-113">하지만 사이트 맵 디자이너에 정의 된 대시보드는 사용자가 액세스할 수 있는 경우이 대시보드 보다 우선 합니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="f80d0-114">사용자가 조직 기본값으로 설정한 대시보드를 볼 수 있도록 하려면 다음 중 하나를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="f80d0-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="f80d0-115">사이트 맵에서 대시보드 설정</span><span class="sxs-lookup"><span data-stu-id="f80d0-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="f80d0-116">해당 사용자에 대 한 사이트 맵 정의 대시보드에 대 한 액세스 권한 제거</span><span class="sxs-lookup"><span data-stu-id="f80d0-116">Remove access to the sitemap defined dashboard for those users</span></span>
