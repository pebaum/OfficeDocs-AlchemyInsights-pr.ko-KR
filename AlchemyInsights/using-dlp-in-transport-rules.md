---
title: 전송 규칙에서 DLP 사용
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5153"
ms.openlocfilehash: 124b031e2e029b745c66a71f681f57134739eafe
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915185"
---
# <a name="using-dlp-in-transport-rules"></a><span data-ttu-id="6211c-102">전송 규칙에서 DLP 사용</span><span class="sxs-lookup"><span data-stu-id="6211c-102">Using DLP in transport rules</span></span>

<span data-ttu-id="6211c-103">데이터 손실 방지(DLP) 기능을 기존의 전송에 통합하려면, 전송 규칙 설정에서 **메시지에 중요한 정보가 포함된 경우....."** 조건을 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="6211c-103">To integrate Data Loss Prevention (DLP) into an existing transport, use the condition "**If the message contains...Sensitive Information**" in the Transport rule setting.</span></span>

<span data-ttu-id="6211c-104">**자세한 내용은 다음을 참조하세요.**</span><span class="sxs-lookup"><span data-stu-id="6211c-104">**For more details, see:**</span></span>

- <span data-ttu-id="6211c-105">전송 규칙에서의 통합 DLP 중요 정보 유형: [중요한 정보 규칙 통합](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/integrate-sensitive-information-rules).</span><span class="sxs-lookup"><span data-stu-id="6211c-105">Integrated DLP sensitive information types in transport rules: [Integrate Sensitive Information Rules](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/integrate-sensitive-information-rules).</span></span>

<span data-ttu-id="6211c-106">규칙에 대한 테스트 모드를 사용하여 정책 테스트를 사용하거나 사용하지 않고 규칙을 테스트할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6211c-106">You can also test the rule with or without policy test using Test Mode on the rule.</span></span>  <span data-ttu-id="6211c-107">규칙을 테스트하기 전에 만든 후 30분간 기다려야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6211c-107">You should wait 30 mins after creating the rule before testing it.</span></span>

- <span data-ttu-id="6211c-108">[메일 흐름/전송 규칙 테스트](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/test-mail-flow-rules)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="6211c-108">See [Test Mail Flow/Transport rules](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/test-mail-flow-rules)</span></span>

<span data-ttu-id="6211c-109">**참고**: EAC에서 전송 규칙을 사용하여 새 DLP 정책을 구현하고자 하는 경우, [보안 및 규정 준수 센터](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide)를 대신 이용합니다.</span><span class="sxs-lookup"><span data-stu-id="6211c-109">**Note**: If you are trying to implement a new DLP policy with transport rules in the EAC, use [DLP Policies in the Security and Compliance center](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide) instead.</span></span>
