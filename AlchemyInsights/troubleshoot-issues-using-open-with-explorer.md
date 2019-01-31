---
title: 탐색기에서 열기를 사용 하 여 문제를 해결
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
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: c95f07b9fb7251442577c014e4005dbe3f92ceb4
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29661757"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="5d516-102">탐색기를 열고 문제 수정</span><span class="sxs-lookup"><span data-stu-id="5d516-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="5d516-103">SharePoint 또는 OneDrive **탐색기에서 열기** 명령을 사용 하 여 문서 라이브러리를 열기와 일반적인 문제를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="5d516-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="5d516-p101">Internet Explorer 10 또는 Internet Explorer 11 사용 합니다. **탐색기에서 열기** Microsoft 지, Google Chrome, Firefox 및 다른 사용자와 호환 없습니다. **탐색기에서 열기** Internet Explorer를 제외한 모든 브라우저에서 비활성화 됩니다.</span><span class="sxs-lookup"><span data-stu-id="5d516-p101">Use Internet Explorer 10 or Internet Explorer 11. **Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others. **Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="5d516-p102">**탐색기에서 열기** 를 SharePoint 라이브러리에 대 한 최신 환경에서 사용할 수 없습니다. **파일 탐색기에서 보기** 를 대신 사용 합니다. **보기 옵션** 을 선택 \> **파일 탐색기의 보기**입니다. 파일 탐색기의 보기 Microsoft 지, Google Chrome, Firefox 및 다른 사용자와 호환 되지 않습니다. **파일 탐색기에서 보기** 에서 Internet Explorer 에서만에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5d516-p102">**Open with Explorer** is not available in the modern experience for SharePoint libraries. Use **View in File Explorer** instead. Select **View options** \> **View in File Explorer**. View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others. **View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="5d516-p103">웹 클라이언트 서비스가 실행 되 고 있는지 확인 합니다. Windows 검색 상자를 실행 하는 형식에서 실행 데스크톱 응용 프로그램을 선택 하 고 services.msc를 입력 한 다음 Enter 키를 누릅니다. 웹 클라이언트 서비스까지 아래로 스크롤한 다음 **상태** 열 "실행 합니다."가 표시 되는지 확인 서비스를 두번클릭 대로 표시 되지 않으면 **시작**을 클릭 한 다음 **확인**을 클릭 합니다. (먼저 **시작 유형** 상자에서 **수동** 또는 **자동** 을 선택 하 여 서비스를 사용 하도록 할 수 있습니다.)</span><span class="sxs-lookup"><span data-stu-id="5d516-p103">Make sure the WebClient service is running. In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter. Scroll down to the WebClient service and make sure the **Status** column displays "Running." If it doesn't, double-click the service, click **Start**, and then click **OK**. (You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="5d516-p104">동기화 하는 것 중 권장 라이브러리 파일 탐색기에서 열기를 복사 하거나 후, 하지만 라이브러리에서 정기적으로 작동 하려면 여러 파일 및 폴더를 이동 해야 하는 경우에 유용 합니다. 파일 탐색기에서 열기 문제를 해결 하려면 [탐색기에서 열기](https://go.microsoft.com/fwlink/?linkid=871665)를 참조 합니다. 동기화를 설정 하는 방법에 대 한 정보를 [새 OneDrive 동기화 클라이언트와 함께 동기화 SharePoint 파일](https://go.microsoft.com/fwlink/?linkid=871666)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5d516-p104">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it. To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="5d516-120">자세한 내용은 [SharePoint Online에서 문제를 해결 하는 "열기와 탐색기" 명령을 사용 하는 방법](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5d516-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) for more information.</span></span> 
  

