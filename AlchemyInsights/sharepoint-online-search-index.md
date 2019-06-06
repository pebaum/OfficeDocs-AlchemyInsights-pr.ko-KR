---
title: SharePoint Online에서 검색 사전 관리
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c2960093bb1cfb649c26528c9f671e6d720ff237
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736058"
---
# <a name="search-in-sharepoint-online"></a><span data-ttu-id="75f94-102">SharePoint Online의 검색</span><span class="sxs-lookup"><span data-stu-id="75f94-102">Search in SharePoint Online</span></span>

<span data-ttu-id="75f94-103">사용자가 SharePoint Online에서 검색 내용을 찾을 수 있도록 콘텐츠를 크롤링한 후 검색 인덱스에 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="75f94-104">콘텐츠는 미리 정의 된 크롤링 일정 (크롤링 일정을 변경할 수 없음)에 따라 자동으로 크롤링됩니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="75f94-105">크롤러는 마지막 크롤링 이후에 변경된 콘텐츠를 선택하고 인덱스를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="75f94-106">콘텐츠가 크롤링되 고 인덱스가 업데이트 되도록 하려면 아래 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-106">To ensure content is crawled and the index is updated, follow the steps below.</span></span>

<span data-ttu-id="75f94-107">사이트 콘텐츠를 검색 가능 하도록 설정 하 여 콘텐츠를 찾을 수 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-107">Make sure content can be found by making site content searchable.</span></span> <span data-ttu-id="75f94-108">자세한 내용은 [사이트에서 콘텐츠를 검색할 수 있도록 설정](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="75f94-108">For more info, see [Enable content on a site to be searchable](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span></span>

<span data-ttu-id="75f94-109">관리 속성을 변경 하거나 크롤링 속성과 관리 속성의 매핑을 변경한 후에는 변경 내용을 검색 인덱스에 반영 하기 전에 사이트를 다시 크롤링되 야 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-109">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

<span data-ttu-id="75f94-110">변경 내용이 실제 사이트가 아니라 검색 스키마에서 이루어지기 때문에 크롤러가 자동으로 사이트에 다시 인덱싱하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-110">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

<span data-ttu-id="75f94-111">자세한 내용은 [사이트, 라이브러리 또는 목록에 대 한 크롤링 수동 요청과 다시 인덱싱](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="75f94-111">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span></span>

 <span data-ttu-id="75f94-112">크롤링을 수동으로 요청한 후 24 시간 이상 기다렸다가 전체 다시 인덱스를 만들어 문제가 발생 했는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-112">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

<span data-ttu-id="75f94-113">크롤링을 시작한 후에 24 시간 이상이 통과 한 경우에는 지원 사례를 기록 하세요.</span><span class="sxs-lookup"><span data-stu-id="75f94-113">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="75f94-114">대부분의 경우에는 이미 솔루션을 사용 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="75f94-115">솔루션을 완료 하려면 최소한 24 시간 이상 기다려 주세요.</span><span class="sxs-lookup"><span data-stu-id="75f94-115">Please give us at least 24 hours to complete a solution.</span></span>

<span data-ttu-id="75f94-116">**중요**: 사이트, 문서 (라이브러리) 또는 목록이 삭제 되어 여전히 검색 결과에 표시 되는 경우 사용자에 게 액세스 하려고 할 때 오류 404 파일을 찾을 수 없습니다. 라는 오류가 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-116">**Important**: If a site, document (library), or a list was deleted and still shows in the search results, users should receive an Error 404 File Not Found when trying to access.</span></span> <span data-ttu-id="75f94-117">이 문제는 추가 조사를 위한 지원 사례로 기록해 야 합니다.</span><span class="sxs-lookup"><span data-stu-id="75f94-117">This issue should be logged as a support case for further investigation.</span></span> 



