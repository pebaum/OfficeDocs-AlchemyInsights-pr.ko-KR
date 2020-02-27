---
title: 모든 전자 메일 catch 만들기
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286198"
---
# <a name="create-an-email-catch-all"></a><span data-ttu-id="2fb8f-102">모든 전자 메일 catch 만들기</span><span class="sxs-lookup"><span data-stu-id="2fb8f-102">Create an email catch all</span></span>

<span data-ttu-id="2fb8f-103">대부분의 경우에는 catch를 사용 하지 않는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-103">Use of a catch all is strongly discouraged.</span></span> <span data-ttu-id="2fb8f-104">보낸 사람에 게 다시 바운스를 제공 하 여 보낸 사람에 게 메시지를 배달 하 여 작업을 수행할 수 있는 것으로 배달할 수 없음을 알리는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-104">It is better to provide a bounce back to the sender letting senders know their message could not be delivered as addressed so they can take action.</span></span> <span data-ttu-id="2fb8f-105">이전에 유효한 전자 메일 주소만 확인 하도록 모니터링 된 사서함을 제한할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-105">You can also limit the monitored mailbox to only catch formerly valid email addresses.</span></span> 

<span data-ttu-id="2fb8f-106">모든 사서함을 파악 하면 적절 한 스팸을 받게 되며 면밀 하 게 모니터링 되지 않으면 결국 채워질 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-106">Any catch all mailbox will receive a good deal of spam and may eventually fill if not closely monitored.</span></span> <span data-ttu-id="2fb8f-107">(수신 제한이 있습니다.)</span><span class="sxs-lookup"><span data-stu-id="2fb8f-107">(There are receiving limits.)</span></span> 

<span data-ttu-id="2fb8f-108">계속 하려면 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-108">If you decide to proceed, follow these steps:</span></span>

1. <span data-ttu-id="2fb8f-109">"모든 받는 사람 유형"을 포함 & 동적 메일 그룹을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-109">Create a Dynamic Distribution Group & include "All Recipient Types."</span></span>

2. <span data-ttu-id="2fb8f-110">Catchall@domain.com과 같은 전자 메일을 catch 하기 위한 전용 사서함을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-110">Create a dedicated Mailbox to catch emails, for example, catchall@domain.com.</span></span>

3. <span data-ttu-id="2fb8f-111">특정 도메인에 대해 DomainType을 "InternalRelay"로 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-111">For the specific domain, set the DomainType to “InternalRelay”.</span></span> <span data-ttu-id="2fb8f-112">나중에 모두 처리를 제거 하는 경우 도메인을 다시 신뢰할 수 있는 것으로 설정 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-112">If you later remove the catch all, be sure to set the domain back to Authoritative.</span></span>

4. <span data-ttu-id="2fb8f-113">메일 흐름 전송 규칙을 만드는 방법은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-113">Create a Mailflow Transport Rule as follows:</span></span>

    - <span data-ttu-id="2fb8f-114">보낸 사람이 "조직 외부" 인 경우</span><span class="sxs-lookup"><span data-stu-id="2fb8f-114">If the Sender is "Outside the Organization"</span></span>
    - <span data-ttu-id="2fb8f-115">메시지를 Catchall@domain.com로 리디렉션</span><span class="sxs-lookup"><span data-stu-id="2fb8f-115">Redirect the message to Catchall@domain.com</span></span>
    - <span data-ttu-id="2fb8f-116">받는 사람이 allusers@domain.com의 구성원 인 경우 제외 (모든 구성원이 포함 된 메일 그룹)</span><span class="sxs-lookup"><span data-stu-id="2fb8f-116">Except if the recipient is a member of allusers@domain.com (Distribution Group contains all members)</span></span>
    - <span data-ttu-id="2fb8f-117">동적 메일 그룹에 새 사서함이 추가 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2fb8f-117">Ensure to validate that new mailboxes are added into the Dynamic Distribution Group</span></span>
