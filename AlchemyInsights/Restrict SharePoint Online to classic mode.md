---
title: SharePoint Online을 클래식 모드로 제한
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: 6a7c0497243ef7425917f54815e61f1244838c54
ms.sourcegitcommit: b14aa00b42ce4ca9d7dc3aa1fd57e66eae115447
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/28/2019
ms.locfileid: "30953350"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="fa7db-102">SharePoint Online을 클래식 모드로 제한</span><span class="sxs-lookup"><span data-stu-id="fa7db-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="fa7db-103">일부 조직은 여전히 클래식 모드 환경을 필요로 합니다.</span><span class="sxs-lookup"><span data-stu-id="fa7db-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="fa7db-104">클래식 모드는 2019 년 4 월 1 일부 터 시작 하 여 더 이상 제거할 계획이 없지만 전체 조직 (테 넌 트)을 목록 및 라이브러리에 대해 클래식 모드로 제한할 수는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="fa7db-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="fa7db-105">관리자는 다음과 같은 수준에서 제공 하는 세분화 된 옵트아웃 스위치를 사용 하 여 클래식 모드에서 개별 목록 및 라이브러리를 관리할 수 있는 다음과 같은 옵션을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="fa7db-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

<span data-ttu-id="fa7db-106">--사이트 모음------------------</span><span class="sxs-lookup"><span data-stu-id="fa7db-106">-- site collection -- site -- list -- library</span></span>

<span data-ttu-id="fa7db-107">또한 현대에서 지원 되지 않는 특정 기능 및 사용자 지정 내용을 사용 하는 목록은 여전히 클래식 모드로 자동 전환 됩니다.</span><span class="sxs-lookup"><span data-stu-id="fa7db-107">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="fa7db-108">4 월 1 일부 터 테 넌 트 옵트아웃의 결과로 클래식 모드에 있는 목록 및 라이브러리는 사이트 수준 및 목록 수준에서 자동으로 관리 됩니다.</span><span class="sxs-lookup"><span data-stu-id="fa7db-108">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="fa7db-109">클래식 모드를 사용 해야 하는 경우 여기 및 PnP Powershell 명령 여기에는 4 월 1 일에 대 한 테 넌 트 수준 옵트아웃 제거를 준비 하는 데 사용할 수 있는 옵션 및 도구에 대 한 자세한 정보를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="fa7db-109">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
