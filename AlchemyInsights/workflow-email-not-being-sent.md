---
title: 워크플로 전자 메일이 전송 되지 않음
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
- "1586"
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059609"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="2e0d2-102">워크플로 전자 메일이 전송 되지 않음</span><span class="sxs-lookup"><span data-stu-id="2e0d2-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="2e0d2-103">워크플로의 전자 메일이 모든 사용자에 게 보내지지 않거나 특정 사용자 에게만 전송 되지 않거나 **전자 메일 메시지를 보낼 수 없습니다. 라는 오류가 표시 됩니다. 전자 메일의 받는 사람이 올바른지 확인**합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

<span data-ttu-id="2e0d2-104">해당 사이트 모음의 **모든** 사용자 권한 그룹 (사용자 정보 목록)에 사용자가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="2e0d2-105">예제 직접 URL: https://<tenant>sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="2e0d2-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

- <span data-ttu-id="2e0d2-106">사용자가 없는 경우 사용자가 페이지에 로그인 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
- <span data-ttu-id="2e0d2-107">외부 사용자 인 경우 초대가 수락 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
- <span data-ttu-id="2e0d2-108">사용자가 사용 권한 그룹에 있는 경우 전자 메일 주소가 올바른지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
- <span data-ttu-id="2e0d2-109">사용자의 전자 메일 주소가 여기에서 설정 되어 있지 않으면 해당 사용자에 대 한 샘플 알림을 만들어 SharePoint의 사용자 프로필에서이 사이트 모음으로 해당 사용자 계정을 강제로 동기화 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="2e0d2-110">워크플로에서 보내는 전자 메일은 사이트 모음 관리자에 게 전송 되 고 다른 사용자에 게는 전달 되지 않으며 \*\*HTTP <spam> <spam>를 사용할 수 \*\* <spam> <spam>없습니다. 라는 오류 메시지가 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

<span data-ttu-id="2e0d2-111">[그룹에 전자 메일을 보낼 때 액세스 거부를](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

<span data-ttu-id="2e0d2-112">또한 **제한 된 액세스 사용자 권한 잠금 모드** 사이트 모음 기능이 활성화 되어 있지 않은지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e0d2-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>

## <a name="related-topics"></a><span data-ttu-id="2e0d2-113">관련 항목</span><span class="sxs-lookup"><span data-stu-id="2e0d2-113">Related topics</span></span>
- [<span data-ttu-id="2e0d2-114">흐름 만들기</span><span class="sxs-lookup"><span data-stu-id="2e0d2-114">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="2e0d2-115">SharePoint 및 흐름</span><span class="sxs-lookup"><span data-stu-id="2e0d2-115">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


