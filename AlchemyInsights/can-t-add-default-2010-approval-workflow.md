---
title: 기본을 추가할 수는 없습니다 2010 승인 워크플로
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2060c9a1-e714-4d93-925e-629c82c35986
ms.openlocfilehash: 758b0339b842478f9609eb716b5b4ddab6579c80
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298464"
---
# <a name="cant-add-default-2010-approval-workflow"></a><span data-ttu-id="12069-102">기본을 추가할 수는 없습니다 2010 승인 워크플로</span><span class="sxs-lookup"><span data-stu-id="12069-102">Can't add default 2010 Approval Workflow</span></span>

<span data-ttu-id="12069-103">Microsoft SharePoint 사이트 모음, 목록 또는 라이브러리에 (예: "승인-SharePoint 2010") 전역적으로 재사용 가능한 워크플로 추가할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="12069-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="12069-104">이 문제를 해결 하려면 다음이 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="12069-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="12069-105">SharePoint Designer 2013의 사이트 모음의 루트 웹사이트를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="12069-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="12069-106">**사이트 개체** **워크플로**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="12069-107">**워크플로** 리본 메뉴의 **새로 만들기** 섹션에서 **다시 사용할 수 있는 워크플로**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="12069-p101">**다시 사용할 수 있는 워크플로 만들기** 양식 이름을 입력 \* \*\*Repair2010\*\*\*. **플랫폼 유형**대 한 **SharePoint 2010 워크플로**선택한 다음 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-p101">On the **Create Reusable Workflow** form, enter the name  \* **Repair2010**\* . For **Platform Type**, select **SharePoint 2010 Workflow**, and then select **OK**.</span></span> 
  
5. <span data-ttu-id="12069-110">**워크플로** 리본 메뉴의 **저장** 섹션에서 **게시**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
6. <span data-ttu-id="12069-p102">**워크플로** 리본 메뉴의 **관리** 섹션에서 **전역적으로 게시**를 선택 합니다. 확인 대화 상자에서 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
7. <span data-ttu-id="12069-p103">웹 브라우저에서 사이트 모음의 루트 웹사이트 찾은 다음 **사이트 설정** 에 액세스 \> **사이트 모음 기능**입니다. 다음 **워크플로** 기능을 설정/해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="12069-115">· 기능이 *활성화 됨* 이면 **비활성화를** 클릭 하 고 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="12069-116">· *비활성화 됨* 의 기능을 사용 하는 경우에 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="12069-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="12069-117">자세한 내용은 다음 [문서](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="12069-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

