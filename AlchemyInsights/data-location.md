---
title: 데이터 위치
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655288"
---
# <a name="data-location"></a><span data-ttu-id="08ac1-102">데이터 위치</span><span class="sxs-lookup"><span data-stu-id="08ac1-102">Data location</span></span>

<span data-ttu-id="08ac1-103">관리 센터에서 또는 PowerShell을 통해 Exchange Online에 연결 하 여 테 넌 트의 위치를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-103">You can view the location of your tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="08ac1-104">**관리 센터:**</span><span class="sxs-lookup"><span data-stu-id="08ac1-104">**Admin center:**</span></span>
1. <span data-ttu-id="08ac1-105">[관리 센터](https://admin.microsoft.com/Adminportal/Home)에 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="08ac1-106">**설정** > **조직 프로필**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="08ac1-107">**데이터 위치**에서 **세부 정보 보기**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="08ac1-108">**슬래시**</span><span class="sxs-lookup"><span data-stu-id="08ac1-108">**PowerShell:**</span></span>
1. <span data-ttu-id="08ac1-109">Windows PowerShell을 사용 하 여 Exchange Online에 연결 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="08ac1-110">[OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet을 실행 하 여 테 넌 트의 속성 목록을 표시 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant's properties.</span></span> 
3. <span data-ttu-id="08ac1-111">조직 id 속성을 살펴봅니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="08ac1-112">EXO 및 SPO에 대 한 데이터 위치가 있으면 [데이터가 있는 위치](https://products.office.com/where-is-your-data-located)에서 사용할 수 있는 다른 서비스에 대 한 데이터 위치를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="08ac1-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>