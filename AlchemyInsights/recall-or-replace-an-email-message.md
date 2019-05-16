---
title: 전자 메일 메시지 회수 또는 교체
ms.author: daeite
author: daeite
manager: joallard
ms.date: 05/15/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 1860
ms.assetid: ''
ms.openlocfilehash: 6e66b5d60fe9ac66c2f2f8f7e99e753652c3a59e
ms.sourcegitcommit: bcb2612ab8ba2aee5165e3912dca95cc1bdd09f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/16/2019
ms.locfileid: "34096550"
---
# <a name="recall-or-replace-an-email-message"></a><span data-ttu-id="0fd06-102">전자 메일 메시지 회수 또는 교체</span><span class="sxs-lookup"><span data-stu-id="0fd06-102">Recall or replace an email message</span></span>

- <span data-ttu-id="0fd06-103">**조직의 사용자에 게 전송 된 메시지만 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-103">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="0fd06-104">예를 들어, 메시지가 Gmail 주소로 전송 된 경우에는 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-104">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="0fd06-105">**PC 용 Outlook 2016에서 보낸 메시지만 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-105">You can **only recall messages sent from Outlook 2016 for the PC**.</span></span> <span data-ttu-id="0fd06-106">사용자가 Outlook for Mac 또는 웹용 Outlook을 사용 하 여 메시지를 보낼 경우에는 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-106">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>
- <span data-ttu-id="0fd06-107">관리자 인 경우 **PowerShell을 사용 하 여 사용자를 대신 하 여 메시지를 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-107">If you're an admin, you can **recall messages on behalf of users by using PowerShell**.</span></span> <span data-ttu-id="0fd06-108">관리 센터에서 메시지를 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-108">You can't recall messages from the admin center.</span></span> <span data-ttu-id="0fd06-109">자세한 내용을 보려면 아래로 스크롤하여 "조직의 전자 메일 메시지 검색 및 삭제"로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-109">Scroll down to "Search for and delete email messages in your organization" for more information.</span></span>

<span data-ttu-id="0fd06-110">***보낸 전자 메일 메시지 회수 또는 교체***</span><span class="sxs-lookup"><span data-stu-id="0fd06-110">***Recall or replace an email message that you sent***</span></span>
1. <span data-ttu-id="0fd06-111">Outlook 창 왼쪽의 폴더 창에서 보낸 편지함 폴더를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-111">In the folder pane on the left of the Outlook window, choose the Sent Items folder.</span></span>
2. <span data-ttu-id="0fd06-112">회수할 메시지를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-112">Open the message that you want to recall.</span></span> <span data-ttu-id="0fd06-113">메시지를 열려면 두 번 클릭 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-113">You must double-click to open the message.</span></span> <span data-ttu-id="0fd06-114">메시지를 읽기 창에 표시 하도록 선택 해도 메시지를 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-114">Selecting the message so it appears in the reading pane won't allow you to recall the message.</span></span>
3. <span data-ttu-id="0fd06-115">메시지 탭에서 **작업** > **회수 메시지**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-115">From the Message tab, select **Actions** > **Recall This Message**.</span></span>
4. <span data-ttu-id="0fd06-116">**이 메시지의 읽지 않은 복사본 삭제** 또는 **읽지 않은 복사본 삭제를 선택 하 고 새 메시지로 바꾼**다음 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-116">Choose **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, then select **OK**.</span></span>
5. <span data-ttu-id="0fd06-117">대체 메시지를 보내는 경우 메시지를 작성 한 다음 **보내기를**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-117">If you’re sending a replacement message, compose the message, then select **Send**.</span></span>
6. <span data-ttu-id="0fd06-118">메시지 회수의 성공 또는 실패는 Outlook의 받는 사람 설정에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-118">The success or failure of a message recall depends on the recipients' settings in Outlook.</span></span> 

<span data-ttu-id="0fd06-119">회수를 확인 하는 방법에 대 한 자세한 내용은 [보낸 전자 메일 메시지 회수 또는 바꾸기를](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0)참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="0fd06-119">For more information, including how to check on the recall, see [Recall or replace an email message that you sent](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="0fd06-120">***조직에서 전자 메일 메시지 검색 및 삭제*** 조직에서 전자 메일 메시지를 검색 하 고 삭제 하려면 전역 관리자 인 경우 가장 간편 합니다. 전역 관리자가 아닌 경우에는 eDiscovery 관리자 역할 그룹 또는 준수 검색 관리 역할에 계정을 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-120">***Search for and delete email messages in your organization*** To search for and delete email messages in your organization, it's easiest if you're a global admin. If you're not a global admin, your account must be added to the eDiscovery Manager role group, or to the Compliance Search management role.</span></span> <span data-ttu-id="0fd06-121">메시지를 삭제 하려면 조직 관리 역할 그룹 또는 검색 및 삭제 관리 역할에 참가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-121">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="0fd06-122">이러한 역할에 대 한 사용 권한은 [Security & 준수 센터](https://protection.office.com/)에서 할당 됩니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-122">Permissions to these roles are assigned in the [Security & compliance center](https://protection.office.com/).</span></span>

1. <span data-ttu-id="0fd06-123">삭제할 메시지를 찾을 [콘텐츠 검색을 만듭니다](https://docs.microsoft.com/en-us/office365/securitycompliance/content-search) .</span><span class="sxs-lookup"><span data-stu-id="0fd06-123">[Create a content search](https://docs.microsoft.com/en-us/office365/securitycompliance/content-search) to find the message to delete.</span></span>
2. <span data-ttu-id="0fd06-124">[Security _AMP_ 준수 센터 PowerShell에 연결](https://docs.microsoft.com/en-us/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps)합니다.</span><span class="sxs-lookup"><span data-stu-id="0fd06-124">[Connect to Security & Compliance Center PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span> 

<span data-ttu-id="0fd06-125">MFA를 사용 하는 경우 [multi-factor authentication을 사용 하 여 Office 365 Security _AMP_ 준수 센터 PowerShell에 연결](https://docs.microsoft.com/en-us/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="0fd06-125">If you're using MFA, see [Connect to Office 365 Security & Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/en-us/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span> 