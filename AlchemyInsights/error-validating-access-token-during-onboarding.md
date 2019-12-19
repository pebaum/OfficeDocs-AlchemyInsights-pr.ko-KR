---
title: 데스크톱 분석을 통해 온-탑재 중에 액세스 토큰 오류 유효성을 검사 하는 동안 오류가 발생 했습니다.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741214"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="f74fe-102">Desktop Analytics 온 보 딩 중 "액세스 토큰 유효성을 검사 하는 동안 오류가 발생 했습니다." 오류</span><span class="sxs-lookup"><span data-stu-id="f74fe-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="f74fe-103">이 오류는 일반적으로 인증 토큰이 만료 되는 경우에 관찰 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f74fe-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="f74fe-104">일반적으로 페이지를 새로 고치면 토큰이 새로 고쳐집니다.</span><span class="sxs-lookup"><span data-stu-id="f74fe-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="f74fe-105">그러나 온보드 데스크톱 분석에 사용 되는 계정에 조건부 액세스 정책이 적용 된 경우에는이 문제가 지속 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f74fe-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="f74fe-106">Azure Portal에서 Azure AD 로그인 로그를 검토 하 여 데스크톱 분석 온 보 딩에 사용 중인 계정에 대 한 로그인 오류가 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f74fe-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="f74fe-107">조건부 액세스에 대 한 자세한 내용은 [조건부 액세스 배포 계획](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="f74fe-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>