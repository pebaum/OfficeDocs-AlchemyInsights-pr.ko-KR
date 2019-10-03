---
title: 모임 정책 설정
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2657"
- "9000734"
ms.openlocfilehash: dac06690b51459ca166c15a5ef0f4c7e7a6d36f0
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376712"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="5cf21-102">Microsoft 팀에서 모임 정책 관리</span><span class="sxs-lookup"><span data-stu-id="5cf21-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="5cf21-103">모임 정책은 조직의 사용자가 예약한 모임에 대해 모임 참가자가 사용할 수 있는 기능을 제어 하는 데 사용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="5cf21-103">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="5cf21-104">모임 정책의 일부 기능은 아직 팀 관리 센터에서 구현 되지 않을 수 있습니다 (설명서에서 "출시 예정" 라는 레이블이 지정 되어 있음).</span><span class="sxs-lookup"><span data-stu-id="5cf21-104">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="5cf21-105">이 경우 또는 "지금은 정책을 업데이트할 수 없지만 나중에 다시 시도 합니다."와 같은 오류가 나타나면 PowerShell을 사용 하 여 팀 회의 정책을 만들거나 수정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="5cf21-105">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="5cf21-106">모임 정책에 대 한 자세한 내용은 다음 리소스를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5cf21-106">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="5cf21-107">정책을 만들고, 변경 하 고, 사용자를 정책에 할당 하는 방법에 대 한 자세한 내용은 [팀에서 모임 정책 관리](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5cf21-107">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="5cf21-108">PowerShell cmdlet을 사용 하 여 정책을 변경 하려면 [팀 Powershell 개요](https://docs.microsoft.com/microsoftteams/teams-powershell-overview)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="5cf21-108">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="5cf21-109">팀 회의 정책에 [비즈니스용 Skype PowerShell 모듈](https://www.microsoft.com/download/details.aspx?id=39366) 을 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="5cf21-109">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="5cf21-110">자세한 내용은 [\*-CsTeamsMeetingPolicy cmdlet 설명서](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) 를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5cf21-110">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

<span data-ttu-id="5cf21-111">**참고:** 정책 변경 내용을 사용자에 게 적용 하는 데 최대 24 시간이 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5cf21-111">**Note:** It can take up to 24 hours for policy changes to take effect for users.</span></span> <span data-ttu-id="5cf21-112">새로 만든 정책을 즉시 변경 하지 못할 수 있습니다. 4 시간을 기다린 후 새로 만든 정책을 다시 수정 해 보십시오.</span><span class="sxs-lookup"><span data-stu-id="5cf21-112">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span> <span data-ttu-id="5cf21-113">여전히 문제가 있는 경우 PowerShell을 사용해 보세요.</span><span class="sxs-lookup"><span data-stu-id="5cf21-113">If you're still having problems, try PowerShell.</span></span>  