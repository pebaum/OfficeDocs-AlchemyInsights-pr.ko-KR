---
title: 2010 승인 워크플로를 추가할 수 없음
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: 3741b1169ddf731725c18fbaed80bfb321e5db46
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32366841"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="d96b7-102">2010 승인 워크플로를 추가할 수 없음</span><span class="sxs-lookup"><span data-stu-id="d96b7-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="d96b7-103">Microsoft SharePoint 사이트 모음에서는 목록 또는 라이브러리에 전역으로 다시 사용 가능한 워크플로 (예: "승인-SharePoint 2010")를 추가할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="d96b7-104">이 문제를 해결 하려면 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="d96b7-105">SharePoint Designer 2013에서 사이트 모음의 루트 웹 사이트를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="d96b7-106">**사이트 개체**에서 **워크플로**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="d96b7-107">**워크플로** 리본 메뉴의 **새로 만들기** 섹션에서 **다시 사용할**수 있는 워크플로를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="d96b7-108">**다시 사용할 수 있는 워크플로 만들기** 양식에서 \* \* *Repair2010* \* \* 이름을 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="d96b7-109">**플랫폼 유형**으로 **SharePoint 2010 워크플로**를 클릭 한 다음 **확인**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="d96b7-110">**워크플로** 리본 메뉴의 **저장** 섹션에서 **게시**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="d96b7-111">**워크플로** 리본 메뉴의 **관리** 섹션에서 **전역으로 게시**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="d96b7-112">확인 대화 상자가 나타나면 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="d96b7-113">웹 브라우저에서 사이트 모음의 루트 웹 사이트를 찾은 다음 **사이트 설정** \> **사이트 모음 기능**에 액세스 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="d96b7-114">**워크플로** 기능을 설정/해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-114">Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="d96b7-115">· 기능이 *활성화* 되 면 **비활성화를** 클릭 한 다음 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="d96b7-116">· 기능이 *비활성화* 되어 있으면 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="d96b7-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="d96b7-117">자세한 내용은 다음 [문서](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d96b7-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

