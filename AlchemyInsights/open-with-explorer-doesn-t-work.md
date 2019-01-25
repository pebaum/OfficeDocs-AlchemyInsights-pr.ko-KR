---
title: 탐색기 열기 작동 하지 않는 경우
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: b55fc7bd5670e655334ef7be368b245c8899633a
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29477729"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="18190-102">탐색기 열기가 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="18190-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="18190-p101">**탐색기에서 열기** 또는 **보기 파일 탐색기에서** 작동 하지 않는 경우에 다음 단계를 수행 하 여 웹 클라이언트 서비스 **실행** 을 위한 설정 되어있는지 확인 합니다. 예는 서비스가 실행 되지 않음 때 SharePoint 또는 OneDrive 라이브러리를 열려면 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="18190-p101">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below. For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="18190-105">Windows 검색 상자를 실행 하는 형식에서 실행 데스크톱 앱, 유형 services.msc 및 선택 한 다음 **Enter**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="18190-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="18190-p102">웹 클라이언트 서비스까지 아래로 스크롤한 다음 **상태** 열을 확인 합니다. 웹 클라이언트 서비스 상태 하지 않으면 **를 실행**하는 경우 서비스를 두번클릭 **시작**을 클릭 한 다음 **확인**을 클릭 합니다. **시작 유형** 상자에서 **수동** 또는 **자동** 을 선택 하 여 필요한 경우 서비스를 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="18190-p102">Scroll down to the WebClient service and check the **Status** column. If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**. Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="18190-p103">파일 탐색기에서 열기 문제를 해결 하려면 [탐색기에서 열기](https://go.microsoft.com/fwlink/?linkid=871665)를 참조 합니다. 더 나은 대신 동기화 탐색: [새 OneDrive 동기화 클라이언트와 함께 동기화 SharePoint 파일](https://go.microsoft.com/fwlink/?linkid=871666)입니다.</span><span class="sxs-lookup"><span data-stu-id="18190-p103">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

