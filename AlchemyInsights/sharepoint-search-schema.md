---
title: SharePoint Online에서 검색 스키마 관리
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: f49195bec64f115063ccfb5256e27fbecd4a54f6
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270118"
---
# <a name="manage-search-schema-in-sharepoint-online"></a><span data-ttu-id="fced2-102">SharePoint Online에서 검색 스키마 관리</span><span class="sxs-lookup"><span data-stu-id="fced2-102">Manage search schema in SharePoint Online</span></span>

<span data-ttu-id="fced2-103">검색 스키마는 사용자가 검색할 수 있는 작업, 사용자가 검색 하는 방법 및 검색 웹 사이트에 결과를 표시 하는 방법을 제어 합니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-103">The search schema controls what users can search for, how users can search it, and how you can present the results on your search websites.</span></span> 

<span data-ttu-id="fced2-104">방법에 대 한 자세한 내용은 [SharePoint Online에서 검색 스키마 관리](https://docs.microsoft.com/sharepoint/manage-search-schema) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="fced2-104">See [Manage the Search Schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema) to learn how to:</span></span> 
- <span data-ttu-id="fced2-105">검색 스키마를 변경 합니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-105">Change the search schema.</span></span>
- <span data-ttu-id="fced2-106">관리 속성을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-106">Create managed properties.</span></span>
- <span data-ttu-id="fced2-107">크롤링 맵 크롤링 속성을 관리 속성에 매핑합니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-107">Map crawled map crawled properties to managed properties.</span></span>

<span data-ttu-id="fced2-108">검색 스키마 관리와 관련 하 여 다음 사항을 확인 하십시오.</span><span class="sxs-lookup"><span data-stu-id="fced2-108">Note the following in regards to managing your Search Schema:</span></span>

- <span data-ttu-id="fced2-109">스키마를 변경할 때 **응용 프로그램이 일시 중지** 되었다는 경고가 표시 되 면 서비스 유지 관리가 수행 되는 동안 일시적 으로만 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-109">If you receive a warning stating **the application is paused** when making a schema change, this is only temporary as there is service maintenance occurring.</span></span> 

    <span data-ttu-id="fced2-110">24 시간 이상 경과 했지만 여전히 경고가 표시 되는 경우 지원 사례를 기록 하세요.</span><span class="sxs-lookup"><span data-stu-id="fced2-110">If more than 24 hours have passed and you still experience the warning, please log a support case.</span></span>
- <span data-ttu-id="fced2-111">관리 속성을 변경 하거나 새로 추가 하는 경우에는 콘텐츠를 다시 크롤링한 후에만 변경 내용이 적용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-111">When you change managed properties or add new ones, the changes take effect only after the content has been re-crawled.</span></span> <span data-ttu-id="fced2-112">SharePoint Online에서 탐색은 정의 된 크롤링 일정에 따라 자동으로 수행 됩니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-112">In SharePoint Online, crawling happens automatically based on the defined crawl schedule.</span></span>
- <span data-ttu-id="fced2-113">변경 내용이 크롤링되 고 있는지 확인 하려면 [목록 또는 라이브러리의 다시 인덱싱을 특별히 요청](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list) 하면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="fced2-113">To make sure that your changes are crawled, you can specifically [request a re-indexing of the list or library](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list)</span></span> 

<span data-ttu-id="fced2-114">검색 스키마에 대 한 전체 개요를 보려면 [검색 스키마 소개](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/) 를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="fced2-114">For a complete overview of the Search Schema, see [Introducing Search Schema](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/)</span></span> 


