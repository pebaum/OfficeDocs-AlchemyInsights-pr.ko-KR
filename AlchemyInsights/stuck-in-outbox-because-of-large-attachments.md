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
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441311"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="64d9d-102">보낼 편지함에 걸린 메시지 수정</span><span class="sxs-lookup"><span data-stu-id="64d9d-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="64d9d-103">[Microsoft 지원 및 복구 도우미](https://diagnostics.office.com/#/) 도구에서 ["전자 메일 메시지 보내기, 받기 또는 찾기에 문제가 발생](https://aka.ms/SaRA-OutlookSendReceive) 했습니다." 시나리오를 실행 하 여 시작 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-103">We recommend that you start by running the scenario ["I’m having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="64d9d-104">보낼 편지함에 메시지가 걸려 가장 많이 발생 하는 이유는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-104">When a message gets stuck in your Outbox, the most likely causes are:</span></span>
- <span data-ttu-id="64d9d-105">큰 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="64d9d-105">Large attachments.</span></span>
- <span data-ttu-id="64d9d-106">**연결 되었을 때 바로 보내기** 옵션을 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-106">The **Send immediately when connected** option is not enabled.</span></span>

<span data-ttu-id="64d9d-107">큰 첨부 파일을 제거 하려면:</span><span class="sxs-lookup"><span data-stu-id="64d9d-107">To remove large attachments:</span></span> 

1. <span data-ttu-id="64d9d-108">Outlook에서 **보내기/받기를** > **오프 라인으로 작업**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-108">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="64d9d-109">탐색 창에서 **보낼 편지함**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-109">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="64d9d-110">여기서는 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-110">From here, you can:</span></span> 
    - <span data-ttu-id="64d9d-111">메시지를 삭제 한 후 선택 하 고 **삭제**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-111">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="64d9d-112">메시지를 임시 보관 함 폴더로 끈 다음, 해당 파일을 두 번 클릭 하 여 열고, 해당 사용자의 선택 사항을 제거한 다음 **삭제**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-112">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="64d9d-113">Outlook에서 메시지 전송을 시도 중 이라는 오류가 표시 되 면 Outlook을 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-113">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="64d9d-114">종료 하는 데 몇 분 정도 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-114">It may take a few moments to exit.</span></span> <span data-ttu-id="64d9d-115">Outlook이 닫히지 않으면 Ctrl + Alt + Delete를 누르고 **작업 관리자 시작**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-115">If Outlook doesn’t close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="64d9d-116">작업 관리자에서 **프로세스** 탭을 선택 하 고 아래로 스크롤하여 outlook .exe를 선택한 다음 **프로세스 끝내기**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-116">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="64d9d-117">Outlook을 닫은 후에 다시 시작 하 고 2 ~ 3 단계를 반복 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-117">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="64d9d-118">첨부 파일을 제거한 후에는**오프 라인으로 작업** **보내기/받기를** > 클릭 하 여 온라인 작업을 다시 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-118">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="64d9d-119">또한 **보내기를**클릭 했지만 연결 되어 있지 않은 경우에도 보낼 편지함에 메시지가 남아 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-119">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="64d9d-120">**보내기/받기를** 클릭 하 고 **오프 라인으로 작업** 단추를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-120">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="64d9d-121">파란색 이면 연결 되어 있지 않은 것입니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-121">If it's blue, you're disconnected.</span></span> <span data-ttu-id="64d9d-122">연결 하려면 선택 하 고 (단추가 흰색으로 바뀜) **모두 보내기를**클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-122">Select it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="64d9d-123">**연결 되었을 때 즉시 보내기를**사용 하도록 설정 하려면:</span><span class="sxs-lookup"><span data-stu-id="64d9d-123">To enable **Send immediately when connected**:</span></span>
 
- <span data-ttu-id="64d9d-124">**파일** > \*\*\*\* 옵션 >  **고급**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-124">Select **File** > **Options** >  **Advanced**.</span></span>
<span data-ttu-id="64d9d-125">**보내기 및 받기** 섹션에서 **연결 되 면 바로 보내기를**선택 하 고 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-125">In the **Send and receive** section, select **Send immediately when connected**, and then choose **OK**.</span></span>
 
<span data-ttu-id="64d9d-126">자세한 내용은 다음을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="64d9d-126">For full details see:</span></span>
- [<span data-ttu-id="64d9d-127">비디오: 걸린 전자 메일 보내기 또는 삭제</span><span class="sxs-lookup"><span data-stu-id="64d9d-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="64d9d-128">Outlook에서 보내기/받기 작업을 수동으로 시작할 때까지 전자 메일이 보낼 편지함 폴더에 남아 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d9d-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
