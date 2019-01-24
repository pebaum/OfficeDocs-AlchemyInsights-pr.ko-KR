---
title: Intune 사용 하 여 조건부 액세스
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478574"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="f712c-102">Intune 사용 하 여 조건부 액세스</span><span class="sxs-lookup"><span data-stu-id="f712c-102">Conditional Access with Intune</span></span>

<span data-ttu-id="f712c-103">**조건부 액세스** 를 사용 하 여 Intune를 사용한 3 단계가 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="f712c-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="f712c-p101">어떤 리소스를 보호 하는, 및 해당 리소스에 액세스 하기 위해 충족 되어야 하는 데 필요한 조건을 정의 하는 **조건부 액세스 정책** 을 만듭니다. 예, 장치를 회사 전자 메일에 액세스 하기 전에 준수 이어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f712c-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="f712c-p102">장치는 준수 것으로 간주 되기 위해 충족 해야 하는 설정을 정의 하는 **규정 준수 정책** 을 만듭니다. 예 전에 규격이 간주 됩니다 장치 최소 6 자리 숫자 pin이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f712c-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="f712c-p103">**규정 준수 정책** 및 **조건부 액세스 정책** 을 모두을 대상으로 하는 원하는 사용자 그룹에 있는지 확인 합니다. Azure Active Directory에서 사용자의 특정 그룹을 만들고 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f712c-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="f712c-110">추가 정보</span><span class="sxs-lookup"><span data-stu-id="f712c-110">Read more:</span></span>
  
- [<span data-ttu-id="f712c-111">조건부 액세스 모범 사례</span><span class="sxs-lookup"><span data-stu-id="f712c-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="f712c-112">조건부 Access 시작</span><span class="sxs-lookup"><span data-stu-id="f712c-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

