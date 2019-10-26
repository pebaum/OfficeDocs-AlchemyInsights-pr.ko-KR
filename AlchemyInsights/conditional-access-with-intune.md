---
title: Intune을 사용한 조건부 액세스
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36505000"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="f280f-102">Intune을 사용한 조건부 액세스</span><span class="sxs-lookup"><span data-stu-id="f280f-102">Conditional Access with Intune</span></span>

<span data-ttu-id="f280f-103">Intune을 사용 하 여 **조건부 액세스** 를 사용 하려면 3 단계가 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="f280f-104">보호할 리소스와 해당 리소스에 액세스 하기 위해 충족 해야 하는 조건을 정의 하는 **조건부 액세스 정책을** 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="f280f-105">예를 들어 회사 전자 메일에 액세스 하기 전에 장치가 규격 이어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="f280f-106">장치가 호환 되는 것으로 간주 되기 전에 충족 해야 하는 설정을 정의 하는 **준수 정책을** 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="f280f-107">예를 들어 장치에는 호환 되는 것으로 간주 되기 전에 6 자리 이상의 pin이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="f280f-108">**준수 정책과** **조건부 액세스 정책이** 원하는 사용자 그룹을 대상으로 하도록 보장 합니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="f280f-109">이를 위해서는 Azure Active Directory에서 특정 사용자 그룹을 만들어야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f280f-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="f280f-110">자세한 내용은 다음을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="f280f-110">Read more:</span></span>
  
- [<span data-ttu-id="f280f-111">조건부 액세스 모범 사례</span><span class="sxs-lookup"><span data-stu-id="f280f-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="f280f-112">조건부 액세스 시작</span><span class="sxs-lookup"><span data-stu-id="f280f-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

