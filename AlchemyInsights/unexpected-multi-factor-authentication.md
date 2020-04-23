---
title: 예기치 않은 다단계 인증
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: ''
ms.custom:
- "1300007"
- "4372"
ms.openlocfilehash: a664bd709062ec1335ebcf1f9adddc8aef917ac1
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766607"
---
# <a name="unexpected-multi-factor-authentication"></a><span data-ttu-id="cbda0-102">예기치 않은 다단계 인증</span><span class="sxs-lookup"><span data-stu-id="cbda0-102">Unexpected multi-factor authentication</span></span>

<span data-ttu-id="cbda0-103">2019년 10월 21일 이후에 테넌트를 생성했으며 MFA에 대한 메시지가 예기치 않게 표시될 경우 테넌트에서 [보안 기본값](https://aka.ms/securitydefaults)이 사용하도록 설정되어 있을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="cbda0-103">If your tenant was created after October 21st, 2019 and you're unexpectedly getting prompted for MFA, you likely have [security defaults](https://aka.ms/securitydefaults) enabled in your tenant.</span></span> 

<span data-ttu-id="cbda0-104">보안 기본값을 관리하려면:</span><span class="sxs-lookup"><span data-stu-id="cbda0-104">To Manage security defaults:</span></span>

1. <span data-ttu-id="cbda0-105">전역 관리자 자격 증명을 사용하여 [관리 센터](https://go.microsoft.com/fwlink/p/?linkid=834822)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="cbda0-105">Sign in to the [admin center](https://go.microsoft.com/fwlink/p/?linkid=834822) with your Global admin credentials.</span></span>

2. <span data-ttu-id="cbda0-106">[Azure Active Directory 속성](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties)으로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="cbda0-106">Go to [Azure Active Directory Properties](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span></span>

3. <span data-ttu-id="cbda0-107">페이지 맨 아래에서 **보안 기본값 관리**를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="cbda0-107">At the bottom of the page, click **Manage Security defaults**.</span></span>

4. <span data-ttu-id="cbda0-108">보안 기본값을 사용하도록 설정하려면 **예**를 클릭하고 사용하지 않도록 설정하려면 **아니요**를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="cbda0-108">Click **Yes** to enable security defaults and **No** to disable security defaults.</span></span>
