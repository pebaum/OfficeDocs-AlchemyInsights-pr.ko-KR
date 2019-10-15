---
title: SharePoint 대규모 목록
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 2/12/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: 222ad554de0d94dcfd4e34e9a2c6aa8ab4e6f81f
ms.sourcegitcommit: d7e1b097d3866782f508527c797426dc56c6ba17
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/14/2019
ms.locfileid: "37488523"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="971ad-102">SharePoint에서 큰 목록 및 라이브러리에 대 한 작업</span><span class="sxs-lookup"><span data-stu-id="971ad-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="971ad-103">SharePoint 목록 및 라이브러리에는 최대 3000만 개의 항목이 포함 될 수 있지만, 항목이 5000 개를 초과 하면 작업을 수행 하려고 할 때 목록 보기 임계값 오류가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="971ad-104">이 임계값은 서비스의 성능을 유지 하기 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="971ad-105">변경할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-105">It can't be changed.</span></span> <span data-ttu-id="971ad-106">이 임계값을 초과 하지 않도록 하려면 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="971ad-107">**최신 사용**</span><span class="sxs-lookup"><span data-stu-id="971ad-107">**Use modern**</span></span>

<span data-ttu-id="971ad-108">최신 환경에서 가장 잘 작동 하는 많은 항목이 표시 되는 보기</span><span class="sxs-lookup"><span data-stu-id="971ad-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="971ad-109">클래식 환경에서 발생할 수 있는 오류를 방지 하려면 [최신 환경을 사용](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="971ad-110">**인덱스 추가**</span><span class="sxs-lookup"><span data-stu-id="971ad-110">**Add indexes**</span></span>

<span data-ttu-id="971ad-111">인덱스가 없는 열을 기준으로 필터링 하거나 정렬 하면 오류 메시지가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="971ad-112">[설정] 메뉴의 **목록 설정** 에서 수동으로 [인덱스를 추가한](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) 다음 **인덱싱된 열**을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="971ad-113">**목록 보기 편집**</span><span class="sxs-lookup"><span data-stu-id="971ad-113">**Edit the list view**</span></span>

<span data-ttu-id="971ad-114">큰 목록으로 작업할 때 오류가 발생 하는 경우 [목록 보기를 편집](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372)합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="971ad-115">다음 네 가지 변경 사항으로 인해 목록 보기 임계값 오류가 제거 됩니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="971ad-116">네 가지 사항을 모두 변경 하 여 모든 오류를 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="971ad-117">여전히 오류가 표시 되는 경우 [큰 목록 및 라이브러리 관리](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59)를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="971ad-118">양쪽에서 **열을 기준으로 첫 번째 정렬** **안** 을 선택한 **다음 열을 기준으로 정렬**합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="971ad-119">**첫 번째 그룹** **둘 다에서 열을 선택 하** 고 열을 **기준으로 그룹화**합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="971ad-120">**요약** 섹션에서 모든 열에 대해 아무것도 선택 하지 **않습니다** .</span><span class="sxs-lookup"><span data-stu-id="971ad-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="971ad-121">**열** 섹션에 표시할 열을 하나만 제외 하 고 모두 선택 취소 합니다.</span><span class="sxs-lookup"><span data-stu-id="971ad-121">Deselect all but one column for display from the **Columns** section.</span></span>

