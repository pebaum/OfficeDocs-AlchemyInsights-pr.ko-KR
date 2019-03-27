---
title: Verify your domain
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: d215f3af0cf4b46b12c8cb51a9572adb00f354e4
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30766354"
---
# <a name="verify-your-domain"></a><span data-ttu-id="29cde-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="29cde-102">Verify your domain</span></span>

 <span data-ttu-id="29cde-103">**레코드가 인터넷을 통해 업데이트 되지 않을 수 있습니다.**</span><span class="sxs-lookup"><span data-stu-id="29cde-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="29cde-104">일반적으로 Microsoft에서 새 레코드를 확인하는 데 몇 분 정도면 되지만 경우에 따라 몇 시간이 걸릴 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="29cde-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="29cde-105">이미 기다린 적이 있는 경우 DNS 호스트의 TXT 확인 레코드에 정확한 값을 복사 하 여 붙여 넣으 했는지 다시 한 번 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="29cde-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="29cde-106">한 가지 일반적인 문제는 레코드의 "MS =" 부분을 포함하지 않는 경우입니다.</span><span class="sxs-lookup"><span data-stu-id="29cde-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="29cde-107">누락하지 않도록 주의하세요!</span><span class="sxs-lookup"><span data-stu-id="29cde-107">We need that too!</span></span>
    
- <span data-ttu-id="29cde-108">일부 DNS 호스트에서는 영역 파일(DNS 레코드가 저장되는 위치)이 인터넷을 통해 업데이트되도록 저장하는 추가 단계를 진행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="29cde-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="29cde-109">Office 365에서 레코드를 보고 확인할 수 있도록 변경 내용을 저장했는지 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="29cde-109">Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>
    

