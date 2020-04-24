---
title: 이름 서버 변경
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 572f8befd84f55cb07a3535852a46e735d3ed620
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706761"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="d54c2-102">Microsoft를 가리키도록 도메인 이름 서버 업데이트</span><span class="sxs-lookup"><span data-stu-id="d54c2-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="d54c2-103">참고: 네임 서버 변경 사항이 전파되는 데 최대 48 시간이 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d54c2-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="d54c2-p101">Microsoft 365에서 도메인을 설정하려면 등록 기관의 이름 서버를 업데이트해야 합니다. 도메인 등록 기관에서 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="d54c2-p101">To set up your domain in Microsoft 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="d54c2-106">도메인 등록 기관 웹 사이트에서 이름 서버를 편집하는 곳을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="d54c2-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="d54c2-107">아래의 값을 갖는 2개의 이름 서버 레코드를 만들거나 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="d54c2-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="d54c2-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="d54c2-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="d54c2-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="d54c2-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="d54c2-110">변경 내용을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="d54c2-110">Save changes.</span></span>

<span data-ttu-id="d54c2-111">다음 문서에서도 자세한 방법을 확인할 수 있습니다. [도메인 등록 기관에서 이름 서버 변경](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="d54c2-111">You can also find detailed instructions in this article: [Change nameservers with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  