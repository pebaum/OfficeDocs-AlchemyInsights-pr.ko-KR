---
title: 비디오 재생에 사용되는 CDN
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002552"
- "5146"
ms.openlocfilehash: 489e92ad8fb38ff6f62db3cb65bfd6d329c63490
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789887"
---
# <a name="cdn-used-for-video-playback"></a><span data-ttu-id="5d414-102">비디오 재생에 사용되는 CDN</span><span class="sxs-lookup"><span data-stu-id="5d414-102">CDN used for video playback</span></span>

<span data-ttu-id="5d414-103">Stream 및 외부 앱의 실시간 이벤트 또는 Yammer/Teams의 장치 실시간 이벤트는 자동으로 Azure CDN을 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="5d414-103">Live events from Stream and External app or device live events from Yammer/Teams will automatically use Azure CDN.</span></span> <span data-ttu-id="5d414-104">Stream에 업로드된 주문형 비디오는 재생을 위해 아직 Azure CDN을 사용하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="5d414-104">On-demand videos uploaded to Stream don't yet use Azure CDN for playback.</span></span> <span data-ttu-id="5d414-105">Stream의 비 실시간 비디오는 테넌트의 지리적 지역에 있는 테넌트와 연결된 Azure Media Services 원본 서버에서 재생됩니다.</span><span class="sxs-lookup"><span data-stu-id="5d414-105">Non-live videos in Stream are played back from the Azure Media Services origin server associated with your tenant in your tenant's geographic region.</span></span> <span data-ttu-id="5d414-106">자세한 내용은 다음을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="5d414-106">For more information, see:</span></span>

- [<span data-ttu-id="5d414-107">비디오 재생에 사용되는 CDN</span><span class="sxs-lookup"><span data-stu-id="5d414-107">CDN used for video playback</span></span>](https://docs.microsoft.com/ko-KR/stream/network-overview#cdn-used-for-video-playback)
