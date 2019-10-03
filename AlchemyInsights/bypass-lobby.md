---
title: 바이패스 로비
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: de665ca6defcd0d00d227435473e5a4ccf61bc82
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376717"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="01e90-102">컨트롤 로비 설정 및 참여 수준 제어</span><span class="sxs-lookup"><span data-stu-id="01e90-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="01e90-103">이러한 설정은 모임에 참가 하기 전에 로비에서 대기 하는 모임 참가자 및 모임에서 허용 되는 참여 수준을 제어 합니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-103">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="01e90-104">Powershell을 사용 하 여 팀 관리 센터에서 아직 구현 되지 않은 모임 정책 설정 ("출시 예정")을 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-104">You can use Powershell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span>  <span data-ttu-id="01e90-105">모든 사용자가 로비를 무시할 수 있도록 하는 예제 PowerShell cmdlet은 아래를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="01e90-105">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>  

- <span data-ttu-id="01e90-106">사용자가 인증 된 사용자가 참석할 수 있을 때까지 사용자가 모임에 직접 참가 하거나 로비에서 대기할지 여부를 제어 하는 이끌이 별 정책 [으로 자동으로 인정](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) 합니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-106">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="01e90-107">[익명 사용자가 모임을 시작할 수 있도록 허용](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) 은 B2B 및 페더레이션 사용자를 비롯 한 익명 사용자가 사용자의 모임에 참석할 수 있는지 여부를 제어 하는 이끌이 별 정책입니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-107">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="01e90-108">전화 [접속 사용자의 로비 사용 허용](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**출시 예정**)은 전화로 전화를 거는 사용자가 모임에 직접 참가할 지 또는 **자동 허용 사용자** 설정에 관계 없이 로비에서 대기할지 여부를 제어 하는 이끌이 별 정책입니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-108">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="01e90-109">[이끌이가 로비 설정 재정의 허용](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**곧 예정**)은 모임 이끌이가 **자동으로 사용자** 를 승인 하 고 전화 접속을 허용 하는 관리자가 설정한 로비 설정을 재정의할 수 있는지 여부를 제어 하는 이끌이 별 정책입니다. \*\* 사용자가\*\* 새 모임을 예약할 때 로비를 우회할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-109">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="01e90-110">**참고:** Microsoft 팀 회의 정책에 대 한 전체 개요를 보려면 [팀에서 모임 정책 관리](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="01e90-110">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span> 


<span data-ttu-id="01e90-111">**PowerShell 예제**</span><span class="sxs-lookup"><span data-stu-id="01e90-111">**PowerShell example**</span></span>

<span data-ttu-id="01e90-112">외부 또는 익명 사용자를 포함 하 여 모든 사용자가 로비를 우회 하도록 허용 하려면 PowerShell을 사용 하 여이 작업을 수행할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-112">If you'd like to allow everyone, including external or anonymous users, to bypass the lobby, you can also use PowerShell to accomplish this task.</span></span>  <span data-ttu-id="01e90-113">다음은 조직에 대 한 전역 모임 정책을 수정 하는 예입니다.</span><span class="sxs-lookup"><span data-stu-id="01e90-113">Here's an example of modifying the global meeting policy for your organization.</span></span>   

<span data-ttu-id="01e90-114">(이를 위해 위의 설명서를 검토 하 여이를 통해 허용 되는 작업을 정확 하 게 파악 해야 합니다.)</span><span class="sxs-lookup"><span data-stu-id="01e90-114">(Be sure to review the documentation above before making these changes to understand exactly what this allows.)</span></span>

<span data-ttu-id="01e90-115">CsTeamsMeetingPolicy-Identity Global-AutoAdmittedUsers "모든 사용자"-AllowPSTNUsersToBypassLobby $True</span><span class="sxs-lookup"><span data-stu-id="01e90-115">Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True</span></span>

<span data-ttu-id="01e90-116">자세한 내용은 [CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="01e90-116">For more information, see [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span></span>
