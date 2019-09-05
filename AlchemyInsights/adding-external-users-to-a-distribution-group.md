---
title: 메일 그룹에 외부 사용자 추가
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: e84a5b04d6fc805deaa47cb10c91081f37411e5b
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/04/2019
ms.locfileid: "36737879"
---
# <a name="add-external-users-to-a-distribution-group"></a><span data-ttu-id="05ed6-102">메일 그룹에 외부 사용자 추가</span><span class="sxs-lookup"><span data-stu-id="05ed6-102">Add external users to a Distribution Group</span></span>

<span data-ttu-id="05ed6-103">DG (메일 그룹)에 외부 연락처를 추가 하는 과정은 두 단계로 진행 됩니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-103">Adding an external contact to a Distribution Group (DG) is a two-step process:</span></span>
  
1. <span data-ttu-id="05ed6-104">외부 사용자에 대 한 메일 연락처를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-104">Create a Mail Contact for the external user:</span></span>
    
    1. <span data-ttu-id="05ed6-105">관리 센터에서 **사용자** > [연락처](https://admin.microsoft.com/adminportal/home#/Contact) 페이지로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-105">In the admin center, go to the **Users** > [Contacts](https://admin.microsoft.com/adminportal/home#/Contact) page.</span></span> 
    
    2. <span data-ttu-id="05ed6-106">**연락처 추가를**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-106">Select **Add a contact**.</span></span>
    
    3. <span data-ttu-id="05ed6-107">연락처에 대 한 정보를 입력 하 고 **추가**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-107">Type the information for your contact and select **Add**.</span></span>
    
2. <span data-ttu-id="05ed6-108">DG에 메일 연락처를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-108">Add the Mail Contact to your DG:</span></span>
    
    1. <span data-ttu-id="05ed6-109">관리 센터에서 **그룹** > [그룹](https://admin.microsoft.com/adminportal/home#/groups) 페이지로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-109">In the admin center, go to the **Groups** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) page.</span></span> 
    
    2. <span data-ttu-id="05ed6-110">외부 사용자를 추가할 DG를 찾아서 선택 하 여 편집 대화 상자를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-110">Find the DG you want to add the external user to, and select it to open the edit dialog.</span></span>
    
    3. <span data-ttu-id="05ed6-111">**구성원** 탭에서 **모두 보기 및 구성원 관리**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-111">On the **Members** tab, select **View all and manage members**.</span></span> 
    
    4. <span data-ttu-id="05ed6-112">**구성원 추가**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-112">Select **Add members**.</span></span>
    
    5. <span data-ttu-id="05ed6-113">이전 단계에서 만든 메일 연락처를 선택한 다음 **저장**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-113">Select the Mail Contact you created on the previous step, and then select **Save**.</span></span>
    
<span data-ttu-id="05ed6-114">이러한 단계를 수행한 후에 외부 사용자가 DG로 전자 메일을 보내거나 보내지 못하는 경우에는 내부 사용자의 전자 메일만 허용 하도록 DG가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-114">If after following these steps your external users can't send emails to the DG or don't receive emails from it, it could be that the DG is marked to only allow emails from internal users.</span></span> <span data-ttu-id="05ed6-115">이 구성을 확인 하 고 [여기에 나와](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online)있는 지침을 따라 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-115">You can check this configuration and fix it following the directions [here](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span></span>
  
 <span data-ttu-id="05ed6-116">**참고:** 그룹 유형이 "Office 365 group" ("메일 그룹")이 아닌 경우에는 이러한 지침이 적용 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-116">**Note:** These instructions don't apply if your group's type is "Office 365 group" instead of "Distribution group."</span></span> <span data-ttu-id="05ed6-117">이 경우 외부 사용자를 Outlook에서 그룹에 직접 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-117">If that is the case, you can add the external user directly to the group from Outlook.</span></span> <span data-ttu-id="05ed6-118">[이 문서](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx)에서는 Office 365 그룹 게스트와 외부 게스트 추가에 대 한 지침을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05ed6-118">Detailed information on Office 365 groups guests as well as instructions for adding external guests can be found in [this article](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span></span>
  