---
title: 조건부 액세스 모니터링
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 374814f4eabd61433a15876ebf7f351819933c21
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36538760"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="840cb-102">Exchange에 대 한 조건부 액세스 모니터링</span><span class="sxs-lookup"><span data-stu-id="840cb-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="840cb-103">조건부 액세스를 사용 하는 사용자는 조직의 액세스 요구 사항을 충족 하지 않는 경우 알림 전자 메일을 받게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="840cb-104">이 문제를 해결 하려면 다음 해결 방법 중 하나 이상을 수행 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="840cb-105">디바이스가 등록 된 것으로 보이면 사용자에 게 회사 포털 앱으로 이동 하 여 회사 포털에 표시 되는지 확인 하도록 권고 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="840cb-106">그렇지 않으면 사용자가 장치를 등록 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="840cb-107">Azure portal에서 \*\* \> Intune 장치 준수\*\*로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="840cb-108">**모니터** 에서 **장치 준수**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="840cb-109">장치 준수 보고서를 확인 하 여 사용자의 장치가 호환 되는 것으로 표시 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="840cb-110">Azure portal에서 \*\* \> Intune 장치 준수\*\*로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="840cb-111">**관리**에서 **정책을**클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="840cb-112">준수 정책 목록에서 사용자의 장치에 프로필이 할당 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="840cb-113">프로필이 할당 되지 않은 경우 Intune에서 장치의 준수 상태를 확인할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="840cb-114">사용자의 조건부 액세스 할당을 편집 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="840cb-115">Azure portal에서 **Intune \> 조건부 액세스 \> 정책** 으로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="840cb-116">목록에서 정책 선택</span><span class="sxs-lookup"><span data-stu-id="840cb-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="840cb-117">**사용자 및 그룹을** 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="840cb-118">특정 정책을 대상으로 지정 하려면 **포함** 목록에 사용자를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="840cb-119">정책이 정책에서 생략 되도록 하려면 해당 사용자를 **제외** 목록에 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="840cb-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="840cb-120">자세한 내용은 다음을 참조 하십시오. [조건부 액세스 장치 모니터링 방법](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="840cb-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

