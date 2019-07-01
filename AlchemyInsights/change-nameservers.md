---
title: 이름 서버 변경
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.assetid: d011531a-0951-49c0-af30-40d2e765f381
ms.openlocfilehash: 148fbee1c14a8da6ede5ec5ccae90b1a4340ce32
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35363083"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="831c3-102">Office 365에서 도메인 이름 서버 업데이트</span><span class="sxs-lookup"><span data-stu-id="831c3-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="831c3-103">참고: 네임 서버 변경 사항이 전파되는 데 최대 48 시간이 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="831c3-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="831c3-p101">Office 365에서 도메인을 설정하려면 등록 기관의 이름 서버를 업데이트해야 합니다. 도메인 등록 기관에서 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="831c3-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="831c3-106">도메인 등록 기관 웹 사이트에서 이름 서버를 편집하는 곳을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="831c3-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="831c3-107">아래의 값을 갖는 2개의 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="831c3-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="831c3-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="831c3-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="831c3-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="831c3-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="831c3-110">변경 내용을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="831c3-110">Save changes.</span></span>

<span data-ttu-id="831c3-111">다음 문서에서도 자세한 방법을 확인할 수 있습니다. [도메인 등록 기관에서 이름 서버를 변경하여 Office 365 설정](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="831c3-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  