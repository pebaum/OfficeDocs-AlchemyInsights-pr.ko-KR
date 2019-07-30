---
title: DNS 레코드를 업데이트하여 현재 호스팅 공급자에 웹 사이트 유지
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "42"
- "43"
- "100002"
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: e437015d476c1417fa37e1b1c250e2205e9ce4d9
ms.sourcegitcommit: b825ced7b66d452b0f3874a57e033e690ec41c93
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/29/2019
ms.locfileid: "35925291"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="d3c13-102">DNS 레코드를 업데이트하여 현재 호스팅 공급자에 웹 사이트 유지</span><span class="sxs-lookup"><span data-stu-id="d3c13-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="d3c13-103">[도메인](https://portal.office.com/adminportal/home#/Domains) 페이지의 도메인 목록에서 웹 사이트에 사용 중인 도메인을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-103">On the [Domains](https://portal.office.com/adminportal/home#/Domains) page, in the list of domains, select the domain you're using for your website.</span></span>

2. <span data-ttu-id="d3c13-104">**+ 새 사용자 지정 레코드** 를 선택하고 다음을 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-104">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="d3c13-105">**DNS 유형** 에 대해 다음을 입력합니다. **A(주소)**</span><span class="sxs-lookup"><span data-stu-id="d3c13-105">For **DNS type** enter: **A (Address)**</span></span>

  - <span data-ttu-id="d3c13-106">**호스트 이름 또는 별칭** 에는 **@** 을 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-106">For **Host name or Alias**, type the following: **@**</span></span>

  - <span data-ttu-id="d3c13-107">**IP 주소** 에는 현재 호스팅되는 웹 사이트의 고정 IP 주소를 입력합니다(예: 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="d3c13-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span>

    <span data-ttu-id="d3c13-p101">이 IP 주소는  *동적*  IP 주소가 아니라 웹 사이트의  *고정*  IP 주소여야 합니다. 웹 사이트가 호스트되는 사이트에서 공개 웹 사이트의 고정 IP 주소를 가져올 수 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-p101">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address. Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span>

3. <span data-ttu-id="d3c13-110">**저장** 을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-110">Select **Save**.</span></span>

<span data-ttu-id="d3c13-111">추가로, 고객이 쉽게 사용자의 웹 사이트를 찾을 수 있도록 CNAME 레코드를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="d3c13-112">**+ 새 사용자 지정 레코드** 를 선택하고 다음을 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-112">Select **+ New custom record** and enter the following:</span></span>

  - <span data-ttu-id="d3c13-113">**DNS 유형** 에 대해 다음을 입력합니다. **CNAME(별칭)**</span><span class="sxs-lookup"><span data-stu-id="d3c13-113">For **DNS type** enter: **CNAME (Alias)**</span></span>

  - <span data-ttu-id="d3c13-114">**호스트 이름 또는 별칭** 에는 **www** 를 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-114">For **Host name or Alias**, type the following: **www**</span></span>

  - <span data-ttu-id="d3c13-115">**대상 주소** 에 웹 사이트의 FQDN(정규화된 도메인 이름)을 contoso.com과 같이 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span>

2. <span data-ttu-id="d3c13-116">**저장**을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d3c13-116">Select **Save**.</span></span>
