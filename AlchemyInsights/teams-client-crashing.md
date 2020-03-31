---
title: Teams 클라이언트의 작동이 중지되나요?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030682"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="2c5d7-102">Teams 클라이언트의 작동이 중지되나요?</span><span class="sxs-lookup"><span data-stu-id="2c5d7-102">Teams client crashing?</span></span>

<span data-ttu-id="2c5d7-103">Teams 클라이언트의 작동이 중단되면 다음을 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="2c5d7-104">Teams 데스크톱 앱을 사용하는 경우 [앱이 완전히 업데이트되었는지 확인합니다](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="2c5d7-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="2c5d7-105">모든 [Office 365 URL과 주소 범위](https://docs.microsoft.com/microsoftteams/connectivity-issues)에 액세스할 수 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-105">Make sure all the [Office 365 URL's and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="2c5d7-106">관리자 계정으로 로그인하고 [서비스 상태 대시보드](https://docs.microsoft.com/office365/enterprise/view-service-health)를 확인하여 작동 중단 또는 서비스 저하가 없는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-106">Log in with your admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

 - <span data-ttu-id="2c5d7-107">마지막 단계로 Teams 클라이언트 캐시를 지울 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-107">As a last step, you can attempt to clear your Teams client cache:</span></span>

    1.  <span data-ttu-id="2c5d7-108">Microsoft Teams 데스크톱 클라이언트를 완전히 종료합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-108">Fully exit the Microsoft Teams desktop client.</span></span> <span data-ttu-id="2c5d7-109">아이콘 트레이에서 **Teams**를 마우스 오른쪽 단추를 클릭하고 **종료**를 클릭하거나 작업 관리자를 실행하여 프로세스를 완전히 종료할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-109">You can right-click **Teams** from the Icon Tray and click **Quit**, or run Task Manager and fully kill the process.</span></span>

    2.  <span data-ttu-id="2c5d7-110">파일 탐색기로 이동한 다음 %appdata%\Microsoft\teams를 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-110">Go to File Explorer, and type in %appdata%\Microsoft\teams.</span></span>

    3.  <span data-ttu-id="2c5d7-111">이 디렉터리에서 다음과 같은 폴더를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-111">Once in the directory, you'll see a few of the following folders:</span></span>

         - <span data-ttu-id="2c5d7-112">**Application Cache**에서 Cache로 이동한 후 캐시 위치 %appdata%\Microsoft\teams\application cache\cache에서 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-112">From within **Application Cache**, go to Cache and delete any of the files in the Cache location:  %appdata%\Microsoft\teams\application cache\cache.</span></span>

        - <span data-ttu-id="2c5d7-113">**Blob_storage**에서 %appdata%\Microsoft\teams\blob_storage의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-113">From within **Blob_storage**, delete all files: %appdata%\Microsoft\teams\blob_storage.</span></span>

        - <span data-ttu-id="2c5d7-114">**Cache**에서 %appdata%\Microsoft\teams\Cache의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-114">From within **Cache**, delete all files: %appdata%\Microsoft\teams\Cache.</span></span>

        - <span data-ttu-id="2c5d7-115">**databases**에서 %appdata%\Microsoft\teams\databases의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-115">From within **databases**, delete all files: %appdata%\Microsoft\teams\databases.</span></span>

        - <span data-ttu-id="2c5d7-116">**GPUCache**에서 %appdata%\Microsoft\teams\GPUcache의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-116">From within **GPUCache**, delete all files: %appdata%\Microsoft\teams\GPUcache.</span></span>

        - <span data-ttu-id="2c5d7-117">**IndexedDB**에서 %appdata%\Microsoft\teams\IndexedDB의 .db 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-117">From within **IndexedDB**, delete the .db file: %appdata%\Microsoft\teams\IndexedDB.</span></span>

        - <span data-ttu-id="2c5d7-118">**Local Storage**에서 %appdata%\Microsoft\teams\Local Storage의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-118">From within **Local Storage**, delete all files: %appdata%\Microsoft\teams\Local Storage.</span></span>

        - <span data-ttu-id="2c5d7-119">마지막으로 **tmp**에서 %appdata%\Microsoft\teams\tmp의 모든 파일을 삭제합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-119">Lastly, from within **tmp**, delete any file: %appdata%\Microsoft\teams\tmp.</span></span>

    4. <span data-ttu-id="2c5d7-120">Teams 클라이언트를 다시 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="2c5d7-120">Restart your Teams client.</span></span>
