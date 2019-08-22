---
title: 탐색기에서 열기 (Explorer가 작동 하지 않음)
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 7680766b53bd5e85789375d3f9e9ab635780ec6c
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36538484"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="12f66-102">탐색기에서 열기 (Explorer가 작동 하지 않음)</span><span class="sxs-lookup"><span data-stu-id="12f66-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="12f66-103">**파일 탐색기에서** 탐색기 또는 보기로 **열기** 가 작동 하지 않는 경우 아래 단계에 따라 WebClient 서비스가 **실행 중** 으로 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="12f66-104">예를 들어 서비스가 실행 되 고 있지 않을 때 SharePoint 또는 OneDrive 라이브러리를 여는 데 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="12f66-105">Windows 검색 상자에 run (실행)을 입력 하 고 데스크톱 앱 실행을 선택한 다음 services.msc를 입력 하 고 **Enter 키**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="12f66-106">아래의 WebClient 서비스로 스크롤한 후 **상태** 열을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="12f66-107">WebClient 서비스 상태가 **실행**되 고 있지 않으면 서비스를 두 번 클릭 하 고 **시작**을 클릭 한 다음 **확인**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="12f66-108">필요한 경우 **시작 유형** 상자에서 **수동** 또는 **자동** 을 선택 하 여 서비스를 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="12f66-109">파일 탐색기에서 열기 문제를 해결 하려면 [탐색기에서 열기](https://go.microsoft.com/fwlink/?linkid=871665)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="12f66-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="12f66-110">보다 나은 대체 방법으로, [새 OneDrive 동기화 클라이언트와 SharePoint 파일 동기화](https://go.microsoft.com/fwlink/?linkid=871666)를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="12f66-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

