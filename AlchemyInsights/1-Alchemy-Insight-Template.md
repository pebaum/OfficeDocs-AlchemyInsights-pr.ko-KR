---
title: 'filename이 가장 동일 [규칙 #-설명]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 1bb1cb35f06e16a2dc85b7e2642b9fa0d203945e
ms.sourcegitcommit: b032c2ac45540b1eb5dd68a4ec7ce1a5d6922f0e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662936"
---
# <a name="required-customer-facing-h1-h2-doesnt-work"></a><span data-ttu-id="58585-102">필요한 고객 마주보는 H1, H2 작동 하지 않는 경우</span><span class="sxs-lookup"><span data-stu-id="58585-102">Required Customer Facing H1, H2 doesn't work</span></span>
<span data-ttu-id="58585-103">예제 텍스트 차단-다음이 지침을 따르십시오.</span><span class="sxs-lookup"><span data-stu-id="58585-103">Example text block - follow these instructions:</span></span>

1. <span data-ttu-id="58585-104">**AlchemyInsights** 폴더의 파일의 파일 이름에서 규칙 ID와 [연금술 파트너 포털](https://alchemyportal.azurewebsites.net) 에서 규칙 이름이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="58585-104">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="58585-p101">예: ***976-How-to-enable-litigation-hold***</span><span class="sxs-lookup"><span data-stu-id="58585-p101">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="58585-p102">서식 파일에으로이 파일의 위쪽에 메타 데이터를 사용 합니다. 다른 nothing이 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="58585-p102">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="58585-109">[연금술 파트너 포털](https://alchemyportal.azurewebsites.net)섹션으로 이동 **고객 견해 제목:** 및는 정보에 대 한 H1 제목에 대 한 사용 가리키는 시작 하기만 합니다.</span><span class="sxs-lookup"><span data-stu-id="58585-109">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="58585-p103">연금술 인 사이트는 단일 H1만 맨 위쪽에 또는 있어야 프로덕션 환경에서 끊어집니다. 그렇게 사용 **굵게** 또는 다른 규칙을 별도 섹션을 나타내기 위해 H2s 렌더링 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="58585-p103">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="58585-112">다음으로, 연금술 규칙 페이지의 고객 인 사이트 섹션에서 초안 자료를 사용 하 여 본문 텍스트를 입력</span><span class="sxs-lookup"><span data-stu-id="58585-112">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="58585-113">글머리 기호 목록은 세밀 하 게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="58585-113">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="58585-114">너무 번호 매기기 목록</span><span class="sxs-lookup"><span data-stu-id="58585-114">Numbered lists too</span></span>
    1. <span data-ttu-id="58585-115">**굵게** 및 *기울임꼴* a-ok 됩니다.</span><span class="sxs-lookup"><span data-stu-id="58585-115">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="58585-116">링크는 항상 있어야 하거나 **"웹에 대 한 링크" 외부 /** OR **UI 요소를 자세히 링크**, 하지 내부 링크입니다.</span><span class="sxs-lookup"><span data-stu-id="58585-116">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="58585-p104">및이 이미 실제로 좀더 너무 깁니다. 모범 사례는 약 400 자--</span><span class="sxs-lookup"><span data-stu-id="58585-p104">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="58585-p105">콘텐츠를 수행할 준비가 되 면 라이브 분기를 가져와 합니다. 그런 다음, [연금술 파트너 포털](https://alchemyportal.azurewebsites.net) 에 이동 하 고 url 필드에 파일 이름을 입력 합니다. 필요한 정보를 검토 하 고 게시 "yes" 라고 표시 되어있는지 확인 하 고 업데이트 규칙을 클릭 합니다. (이 보이는지 곧 출시-포털의 새 버전에서 저렇게.)</span><span class="sxs-lookup"><span data-stu-id="58585-p105">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. (This will look prettier in the new version of the portal - releasing soon.)</span></span>

![url 필드](media/for-content-team.PNG)

