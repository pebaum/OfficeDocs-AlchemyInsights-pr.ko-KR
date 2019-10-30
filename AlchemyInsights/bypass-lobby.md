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
ms.openlocfilehash: bf8be9ffe2bfa45ed2cf149c1c4fa118b40e816d
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768446"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="b9098-102">컨트롤 로비 설정 및 참여 수준 제어</span><span class="sxs-lookup"><span data-stu-id="b9098-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="b9098-103">전화 접속, 외부 및 익명 사용자를 비롯 한 모든 사용자가 Microsoft 팀의 로비를 우회 하도록 허용 하려면 PowerShell을 사용 하 여이 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users to bypass the lobby in Microsoft Teams, you can use PowerShell to do it.</span></span> <span data-ttu-id="b9098-104">다음은 조직에 대 한 전역 모임 정책을 수정 하는 예입니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-104">Here's an example of modifying the global meeting policy for your organization:</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="b9098-105">이 cmdlet은 현재 비즈니스용 Skype PowerShell 모듈을 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="b9098-106">이 cmdlet을 사용 하도록 설정 하려면 [PowerShell을 통해 정책 관리](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="b9098-106">To get setup to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="b9098-107">새 정책을 설정 하 여 사용자에 게 적용 해야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-107">You can set up a new policy, which you'll then need to apply it to users.</span></span> <span data-ttu-id="b9098-108">글로벌 정책을 수정 하면 사용자에 게 자동으로 적용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-108">If you modify the Global policy it'll automatically apply to users.</span></span> <span data-ttu-id="b9098-109">정책이 변경 되는 경우 정책이 적용 되려면 최소 4 시간 및 24 시간까지 기다려야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-109">For any policy change you need to wait at least 4 hours and up to 24 hours for the policies to take effect.</span></span>

<span data-ttu-id="b9098-110">이를 변경 하기 전에 아래의 설명서를 검토 하 여 해당 작업을 정확히 이해 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-110">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>

## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="b9098-111">팀 모임 로비 정책 컨트롤 이해</span><span class="sxs-lookup"><span data-stu-id="b9098-111">Understanding Teams meeting lobby policy controls</span></span>

- <span data-ttu-id="b9098-112">사용자가 인증 된 사용자가 참석할 수 있을 때까지 사용자가 모임에 직접 참가 하거나 로비에서 대기할지 여부를 제어 하는 이끌이 별 정책 [으로 자동으로 인정](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) 합니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-112">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="b9098-113">[익명 사용자가 모임을 시작할 수 있도록 허용](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) 은 B2B 및 페더레이션 사용자를 비롯 한 익명 사용자가 사용자의 모임에 참석할 수 있는지 여부를 제어 하는 이끌이 별 정책입니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-113">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="b9098-114">전화 [접속 사용자의 로비 사용 허용](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**출시 예정**)은 전화로 전화를 거는 사용자가 모임에 직접 참가할 지 또는 **자동 허용 사용자** 설정에 관계 없이 로비에서 대기할지 여부를 제어 하는 이끌이 별 정책입니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-114">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="b9098-115">[이끌이가 로비 설정 재정의 허용](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**곧 예정**)은 모임 이끌이가 **자동으로 사용자** 를 승인 하 고 전화 접속을 허용 하는 관리자가 설정한 로비 설정을 재정의할 수 있는지 여부를 제어 하는 이끌이 별 정책입니다. \*\* 사용자가\*\* 새 모임을 예약할 때 로비를 우회할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b9098-115">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="b9098-116">**참고:** Microsoft 팀 회의 정책에 대 한 전체 개요를 보려면 [팀에서 모임 정책 관리](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="b9098-116">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>
