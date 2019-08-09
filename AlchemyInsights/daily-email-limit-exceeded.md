---
title: 일별 전자 메일 제한이 초과 되었습니다. 워크플로가 일시 중단 되었습니다.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059644"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="59c35-103">일별 전자 메일 제한이 초과 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="59c35-104">워크플로가 일시 중단 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-104">Workflow is suspended.</span></span>

<span data-ttu-id="59c35-105">이 오류는 다음과 같은 시나리오에서 수신 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="59c35-106">Sharepoint Online의 워크플로를 사용 하 2013 2010 고 있으며,이를 수행 하는 사용자</span><span class="sxs-lookup"><span data-stu-id="59c35-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="59c35-107">워크플로는 한 번에 200 명 이상의 사용자에 게 사용자 지정 전자 메일 메시지를 전송 하거나, 하루에 1만 명의 받는 사람을 초과 하거나, 분당 30 개 이상의 메시지를 보내도록 구성 됩니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="59c35-108">워크플로를 실행 하면 전자 메일 메시지가 전송 되지 않으며 다음과 같은 동작이 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="59c35-109">SharePoint 2013 플랫폼 유형을 사용 하는 워크플로의 경우 **워크플로 상태** 페이지로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="59c35-110">워크플로 상태 페이지에서 **내부 상태가** **시작**으로 설정 되 고 정보 풍선이 **받는 사람에 게 메시지를 보낼 수 없는**것으로 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="59c35-111">이 문제를 해결 하려면 [Exchange Online 보낸 사람 제한을](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits)초과 하지 않고 전자 메일 메시지를 보내도록 워크플로를 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="59c35-112">예를 들어 워크플로에서 일시 중지를 사용 하거나, 전자 메일을 Office 365 그룹, 메일 그룹 또는 메일 사용이 가능한 보안 그룹으로 보내거나, 메시지를 한 번에 200 명 미만의 받는 사람에 게 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="59c35-112">For example, use a pause in the workflow, send the email to an Office 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="59c35-113">자세한 내용은 다음 [문서](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="59c35-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="59c35-114">관련 항목</span><span class="sxs-lookup"><span data-stu-id="59c35-114">Related topics</span></span>
- [<span data-ttu-id="59c35-115">흐름 만들기</span><span class="sxs-lookup"><span data-stu-id="59c35-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="59c35-116">SharePoint 및 흐름</span><span class="sxs-lookup"><span data-stu-id="59c35-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 