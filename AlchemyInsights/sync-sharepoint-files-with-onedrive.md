---
title: 새 OneDrive 동기화 클라이언트를 사용하여 SharePoint 파일 동기화
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 5/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 5ad2f1f2-9650-4eb0-b4fa-2f52a09f535a
ms.openlocfilehash: 74b79efeb7e46d03dc55f46252d152cd13e66c84
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34757823"
---
# <a name="sync-sharepoint-files-with-the-new-onedrive-sync-client"></a><span data-ttu-id="7af0a-102">새 OneDrive 동기화 클라이언트를 사용하여 SharePoint 파일 동기화</span><span class="sxs-lookup"><span data-stu-id="7af0a-102">Sync SharePoint files with the new OneDrive sync client</span></span>

<span data-ttu-id="7af0a-103">탐색기에서 열기 명령을 통해 SharePoint 사이트를 호스트하는 서버의 폴더 구조를 표시하는 Windows 탐색기의 로컬 인스턴스를 열 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-103">The Open with Explorer command opens a local instance of Windows Explorer that displays the folder structure on the server that hosts the SharePoint site.</span></span> <span data-ttu-id="7af0a-104">[요청 기반 파일 관리](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e)를 제공하는[ 새 OneDrive 동기화 클라이언트와 SharePoint 파일을 동기화](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a>하는 것이 좋습니다. 파일에 대한 로컬 액세스 권한과 최상의 성능을 제공하기 때문입니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-104">This being said , we recommend [syncing SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) because it provides local access to your files and offers the best performance.</span></span>


<span data-ttu-id="7af0a-105">새 동기화 클라이언트를 사용하는 대신에 탐색기 보기를 사용하도록 선택한 경우 아래 문서의 단계와 모범사례를 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-105">If you chose to use explorer view instead of using the new sync client, ensure you follow the steps and best practices in the articles below.</span></span>

- [<span data-ttu-id="7af0a-106">“탐색기에서 열기” 명령을 사용하여 SharePoint Online의 문제를 해결하는 방법</span><span class="sxs-lookup"><span data-stu-id="7af0a-106">How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online</span></span>](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4)

- [<span data-ttu-id="7af0a-107">탐색기에서 열기를 사용하여 라이브러리 파일 복사 또는 이동</span><span class="sxs-lookup"><span data-stu-id="7af0a-107">Copy or move library files by using Open with Explorer</span></span>](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2)

<span data-ttu-id="7af0a-108">참고: 탐색기에서 열기 단추는 새 라이브러리 환경에 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-108">Note:  The Open with Explorer button doesn't appear in the new library experience.</span></span> <span data-ttu-id="7af0a-109">오른쪽 위의 보기 드롭다운(현재 보기에 따라 드롭다운 이름이 변경됨)을 클릭한 다음, 파일 탐색기에서 보기를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-109">Click the View drop-down in the upper right (the name of the drop-down changes depending on your current view), and then click View in File Explorer.</span></span>

 <span data-ttu-id="7af0a-110">SharePoint 탐색기에서 열기는 ActiveX 컨트롤을 사용하므로 Internet Explorer 10 또는 11에서만 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-110">SharePoint Open with Explorer uses ActiveX controls, so it's only supported in Internet Explorer 10 or 11.</span></span> <span data-ttu-id="7af0a-111">탐색기에서 열기는 Microsoft Edge가 포함된 Windows, Google Chrome, Mozilla Firefox, 또는 Mac 플랫폼에서 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-111">Open with Explorer doesn't work in Windows with Microsoft Edge, Google Chrome, Mozilla Firefox, or on the Mac platform.</span></span> <span data-ttu-id="7af0a-112">이러한 이유로, 탐색기 보기 옵션은 회색으로 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7af0a-112">Due to this reason, the Explorer View option may be grayed out.</span></span>

- <span data-ttu-id="7af0a-113">[SharePoint 리본 단추를 사용할 수 없거나 비활성화된 이유](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca)</span><span class="sxs-lookup"><span data-stu-id="7af0a-113">[Why SharePoint ribbon buttons are unavailable or grayed out](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span></span>
  

