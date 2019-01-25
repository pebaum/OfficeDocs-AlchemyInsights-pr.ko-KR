---
title: Change nameservers
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d011531a-0951-49c0-af30-40d2e765f381
ms.openlocfilehash: b296e76c3d39cad16f329215f0480ae260e77f2e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29477874"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="38a54-102">Office 365에서 도메인 이름 서버 업데이트</span><span class="sxs-lookup"><span data-stu-id="38a54-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="38a54-103">참고: 이름 서버 변경 내용을 전파할 48 시간까지를 대신 하는 경우가 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="38a54-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="38a54-p101">Office 365에서 도메인을 설정하려면 등록 기관의 이름 서버를 업데이트해야 합니다. 도메인 등록 기관에서 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="38a54-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="38a54-106">도메인 등록 기관 웹 사이트에서 이름 서버를 편집하는 곳을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="38a54-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
    
2. <span data-ttu-id="38a54-107">아래의 값을 갖는 2개의 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="38a54-107">Create or edit two nameserver records to match these values:</span></span>
    
  - <span data-ttu-id="38a54-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="38a54-108">ns1.bdm.microsoftonline.com</span></span>
    
  - <span data-ttu-id="38a54-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="38a54-109">ns2.bdm.microsoftonline.com</span></span>
    
3. <span data-ttu-id="38a54-110">변경 내용을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="38a54-110">Save changes.</span></span>
    
<span data-ttu-id="38a54-111">다음 문서에서도 자세한 방법을 확인할 수 있습니다. [도메인 등록 기관에서 이름 서버를 변경하여 Office 365 설정](https://support.office.com/article/https://support.office.com/en-us/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="38a54-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/https://support.office.com/en-us/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  

