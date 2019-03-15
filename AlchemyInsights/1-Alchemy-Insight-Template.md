---
title: 'filename과 같습니다 [RULE #-Description]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e248c2ee3cbb9a86f21c1f36be10c893df76ff52
ms.sourcegitcommit: 3070905131e6d8449981231a3551c0bb4ca38ae6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/14/2019
ms.locfileid: "30634510"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="101bb-102">필수 Alchemy 헤더 H1, H2's이 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="101bb-103">Alchemy 작성을 위한 모범 사례 및 지침:</span><span class="sxs-lookup"><span data-stu-id="101bb-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="101bb-104">**Alchemy Insights를 폴더에 중첩 하지 마세요**-url 구조가 손상 됩니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="101bb-105">여기서는이 문제를 해결 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="101bb-106">**AlchemyInsights** 폴더의 파일에는 파일 이름에 [Alchemy 파트너 포털](https://alchemyportal.azurewebsites.net) 의 규칙 ID와 규칙 이름이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="101bb-107">ex.</span><span class="sxs-lookup"><span data-stu-id="101bb-107">ex.</span></span> <span data-ttu-id="101bb-108">***976-사용 권한 소송-보존***</span><span class="sxs-lookup"><span data-stu-id="101bb-108">***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="101bb-109">이 파일의 맨 위에 있는 메타 데이터를 서식 파일로 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-109">Use the metadata at the top of this file as your template.</span></span> <span data-ttu-id="101bb-110">다른 항목은 필요 없습니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-110">Nothing else is required.</span></span>
1. <span data-ttu-id="101bb-111">[Alchemy 파트너 포털](https://alchemyportal.azurewebsites.net)에서 **고객 통찰력 제목** 섹션으로 이동한 다음 해당 내용을 H1 제목에 대 한 시작 점으로 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="101bb-112">Alchemy Insights는 맨 위에 단일 H1만 포함 되거나 프로덕션에서 중단 됩니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-112">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="101bb-113">H2s은 렌더링 되지 않으므로 별도의 섹션을 나타내기 위해 **굵게** 또는 기타 규칙을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-113">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="101bb-114">다음으로, Alchemy 규칙 페이지의 Customer Insights 섹션에 있는 초안 자료를 사용 하 여 본문 텍스트를 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="101bb-115">글머리 기호 목록이 양호 함</span><span class="sxs-lookup"><span data-stu-id="101bb-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="101bb-116">번호 매기기 목록만 너무 많이 있음</span><span class="sxs-lookup"><span data-stu-id="101bb-116">Numbered lists too</span></span>
    1. <span data-ttu-id="101bb-117">**굵게** 및 *기울임꼴로* 표시 되는-정상</span><span class="sxs-lookup"><span data-stu-id="101bb-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="101bb-118">링크는 항상 내부 링크가 아니라 **UI 요소에 대**한 **"웹 연결"/외부** 또는 딥 링크 중 하나 여야 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="101bb-119">이는 실제로 너무 긴 시간입니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-119">And this is really already a bit too long.</span></span> <span data-ttu-id="101bb-120">모범 사례는 약 400 자---------------------------------</span><span class="sxs-lookup"><span data-stu-id="101bb-120">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="101bb-121">콘텐츠가 준비 되 면 라이브 분기로 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-121">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="101bb-122">그런 다음 [Alchemy 파트너 포털로](https://alchemyportal.azurewebsites.net) 이동 하 여 url 필드에 파일 이름을 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-122">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="101bb-123">"예" 라는 통찰력을 검토 하 고 게시 했는지 확인 한 다음 규칙 업데이트를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="101bb-123">Make sure Insight reviewed and published says "yes" and then click Update Rule.</span></span> <span data-ttu-id="101bb-124">**(이는 곧 포털의 새 버전에서 출시 되는 prettier를 확인 합니다.)** 
 ![url 필드](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="101bb-124">**(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>

