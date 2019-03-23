---
title: Office 365으로 공용 폴더 데이터 마이그레이션
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/26/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a9be935-d798-4b5f-a1b8-15b1f25d1451
ms.openlocfilehash: 0b970917e53fce266e0a16100f3deb869f9f7007
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30754728"
---
# <a name="migrate-public-folder-data-to-office-365"></a><span data-ttu-id="eb6cb-102">Office 365으로 공용 폴더 데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="eb6cb-102">Migrate public folder data to Office 365</span></span>

<span data-ttu-id="eb6cb-103">office 365로 이동할 공용 폴더가 몇 개 밖에 없는 경우 가장 쉬운 방법은 PST 파일에 데이터를 복사한 다음 Office 365로 가져오는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="eb6cb-103">If you have only a few public folders to move to Office 365, the easiest way is to copy the data into PST files and then import them into Office 365.</span></span> <span data-ttu-id="eb6cb-104">실제로 데이터 양이 적은 경우에는 공용 폴더를 PST 파일로 간편 하 게 끌어 놓을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb6cb-104">For a really small amount of data, a simple drag and drop of public folder into a PST file can work.</span></span> <span data-ttu-id="eb6cb-105">더 많은 정보를 제공 하는 경우 (최대 30gb), 폴더를 PST 파일로 내보내는 데 사용할 수 있는 [프로세스를 문서화](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx#PSTMigrate) 했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb6cb-105">If you have more information (up to 30GB) we have [documented a process](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx#PSTMigrate) you can use to export folders to PST files.</span></span> 
  
<span data-ttu-id="eb6cb-106">공용 폴더를 Office 365로 이동 하는 대규모 조직의 경우 몇 가지 가이드를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb6cb-106">For larger organizations that are moving public folders into Office 365, we have several guides available:</span></span>
  
- [<span data-ttu-id="eb6cb-107">레거시 공용 폴더 마이그레이션 (Exchange 2010 이전 버전)</span><span class="sxs-lookup"><span data-stu-id="eb6cb-107">Migrate legacy public folders (Exchange 2010 and earlier)</span></span>](https://technet.microsoft.com/library/dn874017%28v=exchg.150%29.aspx)
    
- [<span data-ttu-id="eb6cb-108">Exchange 2013 공용 폴더 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="eb6cb-108">Migrate Exchange 2013 public folders</span></span>](https://technet.microsoft.com/library/mt798260%28v=exchg.150%29.aspx)
    
- [<span data-ttu-id="eb6cb-109">Exchange 2016 공용 폴더 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="eb6cb-109">Migrate Exchange 2016 public folders</span></span>](https://technet.microsoft.com/library/mt798260%28v=exchg.160%29.aspx)
    
<span data-ttu-id="eb6cb-110">또한 [공용 폴더를 Office 365 그룹으로 마이그레이션하](https://technet.microsoft.com/library/mt843872%28v=exchg.150%29.aspx)는 옵션도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb6cb-110">You also have the option of [Migrating public folders to Office 365 Groups](https://technet.microsoft.com/library/mt843872%28v=exchg.150%29.aspx).</span></span>
  

