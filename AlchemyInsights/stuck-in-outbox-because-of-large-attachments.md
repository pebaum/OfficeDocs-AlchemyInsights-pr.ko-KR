---
title: 대용량 첨부 파일 때문에 보낼 편지함에서 중지
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241258"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="eeb63-102">보낼 편지함에 걸린 메시지 수정</span><span class="sxs-lookup"><span data-stu-id="eeb63-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="eeb63-103">[Microsoft 지원 및 복구 도우미](https://diagnostics.office.com/#/) 도구에서 ["전자 메일 메시지 보내기, 받기 또는 찾기에 문제가 발생](https://aka.ms/SaRA-OutlookSendReceive) 했습니다." 시나리오를 실행 하 여 시작 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="eeb63-104">메시지가 보낼 편지함에 걸려 있으면 첨부 파일이 크거나 "연결 되 면 즉시 보내기" 옵션이 설정 되어 있지 않은 것입니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="eeb63-105">**큰 첨부 파일 제거**</span><span class="sxs-lookup"><span data-stu-id="eeb63-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="eeb63-106">Outlook에서 **보내기/받기를** > **오프 라인으로 작업**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-106">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="eeb63-107">탐색 창에서 **보낼 편지함**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-107">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="eeb63-108">여기서는 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-108">From here, you can:</span></span> 
    - <span data-ttu-id="eeb63-109">메시지를 삭제 한 후 선택 하 고 **삭제**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-109">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="eeb63-110">메시지를 임시 보관 함 폴더로 끈 다음, 해당 파일을 두 번 클릭 하 여 열고, 해당 사용자의 선택 사항을 제거한 다음 **삭제**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-110">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="eeb63-111">Outlook에서 메시지 전송을 시도 중 이라는 오류가 표시 되 면 Outlook을 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-111">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="eeb63-112">종료 하는 데 몇 분 정도 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-112">It may take a few moments to exit.</span></span> <span data-ttu-id="eeb63-113">Outlook이 닫히지 않으면 Ctrl + Alt + Delete를 누르고 **작업 관리자 시작**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-113">If Outlook doesn't close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="eeb63-114">작업 관리자에서 **프로세스** 탭을 선택 하 고 아래로 스크롤하여 outlook .exe를 선택한 다음 **프로세스 끝내기**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-114">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="eeb63-115">Outlook을 닫은 후에 다시 시작 하 고 2 ~ 3 단계를 반복 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-115">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="eeb63-116">첨부 파일을 제거한 후에는**오프 라인으로 작업** **보내기/받기를** > 클릭 하 여 온라인 작업을 다시 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-116">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="eeb63-117">또한 **보내기를**클릭 했지만 연결 되어 있지 않은 경우에도 보낼 편지함에 메시지가 남아 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-117">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="eeb63-118">**보내기/받기를** 클릭 하 고 **오프 라인으로 작업** 단추를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-118">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="eeb63-119">파란색 이면 연결 되어 있지 않은 것입니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-119">If it's blue, you're disconnected.</span></span> <span data-ttu-id="eeb63-120">단추를 클릭 하 여 연결 (단추가 흰색으로 바뀜) 하 고 **모두 보내기를**클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-120">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="eeb63-121">**연결 되 면 즉시 보내기 사용**</span><span class="sxs-lookup"><span data-stu-id="eeb63-121">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="eeb63-122">파일 탭에서 **옵션**을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-122">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="eeb63-123">Outlook 옵션 대화 상자에서 **고급**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-123">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="eeb63-124">보내기 및 받기 섹션에서 **연결 되 면 즉시 보내기를**사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-124">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="eeb63-125">**확인**을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-125">Click **OK**.</span></span>
 
<span data-ttu-id="eeb63-126">자세한 내용은 다음을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="eeb63-126">For full details, see:</span></span>
- [<span data-ttu-id="eeb63-127">비디오: 걸린 전자 메일 보내기 또는 삭제</span><span class="sxs-lookup"><span data-stu-id="eeb63-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="eeb63-128">Outlook에서 보내기/받기 작업을 수동으로 시작할 때까지 전자 메일이 보낼 편지함 폴더에 남아 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eeb63-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
