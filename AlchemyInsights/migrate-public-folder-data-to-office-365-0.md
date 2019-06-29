---
title: Office 365으로 공용 폴더 데이터 마이그레이션
ms.author: dmaguire
author: msdmaguire
manager: dansimp
ms.date: 5/9/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "639"
- "3500007"
ms.assetid: 6e536c7d-ab36-413e-9702-63e51adb3452
ms.openlocfilehash: 4e870f153b37e141aa641c4a85a8d759a600ceed
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380007"
---
# <a name="migrate-public-folder-data-to-office-365"></a><span data-ttu-id="8713d-102">Office 365으로 공용 폴더 데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="8713d-102">Migrate public folder data to Office 365</span></span>

<span data-ttu-id="8713d-103">Office 365로 가져올 공용 폴더가 많지 않은 경우이를 가져오는 가장 쉬운 방법은 데이터를에 복사 하는 것입니다. PST 파일을 선택한 다음 Office 365로 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="8713d-103">If you don't have a lot of public folders to bring into Office 365, the easiest way to bring them would be to copy the data into .PST files and then import them into Office 365.</span></span> <span data-ttu-id="8713d-104">데이터 양이 적은 경우에는 공용 폴더를로 간편 하 게 끌어 놓으면 됩니다. PST 파일의 경우에는 충분 합니다.</span><span class="sxs-lookup"><span data-stu-id="8713d-104">For small amounts of data, a simple drag and drop of public folder into a .PST file can be sufficient.</span></span> <span data-ttu-id="8713d-105">더 많은 데이터 (최대 30GB)를 사용 하는 경우에는 폴더를 PST 파일로 내보내는 데 사용할 수 있는 [프로세스에 대해 설명](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx) 했습니다.</span><span class="sxs-lookup"><span data-stu-id="8713d-105">If you have more data than that (up to 30GB), we have [documented a process](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx) that you can use to export folders to PST files.</span></span>
  
<span data-ttu-id="8713d-106">공용 폴더를 Office 365으로 이동 하는 대규모 조직의 경우 몇 가지 가이드를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8713d-106">For larger organizations who are moving public folders into Office 365, we have several guides available:</span></span>
  
- <span data-ttu-id="8713d-107">[레거시 공용 폴더 마이그레이션](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx) (Exchange 2010 이전 버전)</span><span class="sxs-lookup"><span data-stu-id="8713d-107">[Migrate legacy public folders](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx) (Exchange 2010 and earlier)</span></span>

- [<span data-ttu-id="8713d-108">Exchange 2013 공용 폴더 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="8713d-108">Migrate Exchange 2013 public folders</span></span>](https://technet.microsoft.com/library/mt798260%28v=exchg.150%29.aspx)

- [<span data-ttu-id="8713d-109">Exchange 2016 공용 폴더 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="8713d-109">Migrate Exchange 2016 public folders</span></span>](https://technet.microsoft.com/library/mt798260%28v=exchg.160%29.aspx)

<span data-ttu-id="8713d-110">또한 [공용 폴더를 Office 365 그룹으로 마이그레이션하](https://technet.microsoft.com/library/mt843872%28v=exchg.150%29.aspx)는 옵션도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8713d-110">You also have the option to [migrate public folders to Office 365 Groups](https://technet.microsoft.com/library/mt843872%28v=exchg.150%29.aspx).</span></span>
  