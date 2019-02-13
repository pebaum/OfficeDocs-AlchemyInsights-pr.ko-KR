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
ms.custom: Adm_O365
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: 7332650d1763e2bbd13be48f406fb04b8849a6c1
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29911238"
---
# <a name="verify-your-domain"></a><span data-ttu-id="ca217-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="ca217-102">Verify your domain</span></span>

 <span data-ttu-id="ca217-103">**아마도 레코드가 인터넷을 통해 업데이트 하지 않은 합니다.**</span><span class="sxs-lookup"><span data-stu-id="ca217-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="ca217-104">일반적으로 Microsoft에서 새 레코드를 확인하는 데 몇 분 정도면 되지만 경우에 따라 몇 시간이 걸릴 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ca217-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="ca217-p101">이미 긴 대기한 했을 때, 복사 하 고 DNS 호스트에서 TXT 확인 레코드에 정확한 값을 붙여넣을 했을 때 있는지 다시 확인 하십시오. 일반적인 문제는 포함 하지 않는 "MS ="는 레코드의 일부입니다. 필요한는 너무!</span><span class="sxs-lookup"><span data-stu-id="ca217-p101">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host. One common issue is not including the "MS=" part of the record. We need that too!</span></span>
    
- <span data-ttu-id="ca217-p102">일부 DNS 호스트에서 해야 (DNS 레코드가 저장 됨) 영역 파일을 저장 하기 위해 추가 단계를 수행 하 여 인터넷을 통해 업데이트 됩니다. Office 365에서 참조 하 고 레코드를 확인할 수 있도록 변경 내용을 저장 한 있는지 확인 하십시오.</span><span class="sxs-lookup"><span data-stu-id="ca217-p102">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet. Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>
    

