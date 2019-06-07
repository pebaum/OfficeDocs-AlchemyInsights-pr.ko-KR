---
title: SharePoint Online 권한 수준
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760698"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="aef2a-102">SharePoint Designer 연결 문제</span><span class="sxs-lookup"><span data-stu-id="aef2a-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="aef2a-103">SharePoint Designer에 SharePoint 사이트에 대 한 연결 문제가 발생 한 경우 다음 일반 솔루션을 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="aef2a-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please attempt the following common solutions.</span></span>

<span data-ttu-id="aef2a-104">1 단계: SharePoint Designer가 업데이트 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-104">Step 1: Verify SharePoint Designer is updated.</span></span>

- [<span data-ttu-id="aef2a-105">SharePoint Designer 2013</span><span class="sxs-lookup"><span data-stu-id="aef2a-105">SharePoint Designer 2013</span></span>](https://www.microsoft.com/download/details.aspx?id=35491)

- [<span data-ttu-id="aef2a-106">SharePoint Designer SP1 (서비스 팩 1)</span><span class="sxs-lookup"><span data-stu-id="aef2a-106">SharePoint Designer Service Pack 1 (SP1)</span></span>](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [<span data-ttu-id="aef2a-107">SharePoint Designer 2013에 대 한 업데이트 (KB3114721)</span><span class="sxs-lookup"><span data-stu-id="aef2a-107">Update for SharePoint Designer 2013 (KB3114721)</span></span>](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

<span data-ttu-id="aef2a-108">2 단계: 로컬 캐시 파일 지우기</span><span class="sxs-lookup"><span data-stu-id="aef2a-108">Step 2: Clear the local cache files</span></span>

- <span data-ttu-id="aef2a-109">SharePoint Designer 2013을 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-109">Close SharePoint Designer 2013.</span></span>

- <span data-ttu-id="aef2a-110">로컬 컴퓨터에서 다음 폴더로 이동 하 여 캐시 된 파일을 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-110">On the local computer, browse to the following folders to remove cached files.</span></span>

- <span data-ttu-id="aef2a-111">시작, 실행을 차례로 클릭 하 고 아래의 각 위치에서 찾은 모든 파일을 삭제 합니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-111">Click Start, Run and delete all files found under each of the below locations.</span></span>

<span data-ttu-id="aef2a-112">%APPDATA%\Microsoft\Web Server Extensions\Cache%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="aef2a-112">%APPDATA%\Microsoft\Web Server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

<span data-ttu-id="aef2a-113">SharePoint Designer 2013를 열고 계정을 다시 입력 하 여 작동 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-113">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="aef2a-114">3 단계: [Windows 장치에서 Office 2013에 대 한 최신 인증을 사용 하도록 설정](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="aef2a-114">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span></span>

<span data-ttu-id="aef2a-115">4 단계: 관리자는 SharePoint Designer 연결을 허용 하는 사용자 지정 스크립트를 허용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="aef2a-115">Step 4: Administrators will need to Allow Custom Script to allow the SharePoint Designer connection.</span></span>

<span data-ttu-id="aef2a-116">자세한 단계는 [허용 또는 금지 사용자 지정 스크립트](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="aef2a-116">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


