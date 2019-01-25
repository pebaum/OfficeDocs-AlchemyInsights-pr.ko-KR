---
title: 조건부 액세스를 모니터링합니다.
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29477747"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="ba9a1-102">조건부 액세스를 모니터링합니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="ba9a1-p101">조건부 액세스할 수 있는 대상으로 하는 사용자가 조직의 액세스 요구를 충족 하지 않는 경우 알림 전자 메일을 받게 됩니다. 를 해결 하려면 다음 방법 중 하나 이상을 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="ba9a1-p102">장치는 등록으로 간주 되며, 하는 경우 회사 포털 응용 프로그램으로 이동 하 고 회사 포털에 나타나는지 확인 하는 사용자에 게 알려줍니다. 그렇지 않은 경우 사용자는 장치를 등록을 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="ba9a1-p103">Azure 포털에서로 이동 **Intune \> 장치 준수**합니다. **모니터** 에서 **장치 규정 준수**를 클릭 합니다. 사용자의 장치 규격으로 표시 되어 있는지 확인 하려면 장치 준수 보고서 보기</span><span class="sxs-lookup"><span data-stu-id="ba9a1-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="ba9a1-p104">Azure 포털에서로 이동 **Intune \> 장치 준수**합니다. **관리** **정책**을 클릭 합니다. 규정 준수 정책 목록에서 프로필을 사용자의 장치에 할당 되어 있는지를 확인 합니다. 프로필이 할당 된 다음 Intune 장치의 규정 준수 상태를 확인 하려면 수 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="ba9a1-114">사용자의 조건부 액세스 할당을 편집 합니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="ba9a1-115">Azure 포털에서로 이동 **Intune \> 조건부 액세스 \> 정책**</span><span class="sxs-lookup"><span data-stu-id="ba9a1-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="ba9a1-116">목록에서 정책을 선택합니다</span><span class="sxs-lookup"><span data-stu-id="ba9a1-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="ba9a1-117">**사용자 및 그룹을** 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="ba9a1-p105">특정 정책을 다른 사용자를 대상에 **포함** 목록에 추가 합니다. 정책에서 사용자를 생략 하면 되도록 **제외** 목록에 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="ba9a1-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="ba9a1-120">자세한: [장치에 모니터 조건부 액세스 하는 방법](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="ba9a1-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span></span>
  

