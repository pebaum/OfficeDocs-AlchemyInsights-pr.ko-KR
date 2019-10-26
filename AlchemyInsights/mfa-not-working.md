---
title: MFA 문제
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 276f6b2212c9d85df726cb46a46dee7828b34c89
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36545177"
---
# <a name="issues-with-mfa"></a><span data-ttu-id="feccd-102">MFA 문제</span><span class="sxs-lookup"><span data-stu-id="feccd-102">Issues with MFA</span></span>
<span data-ttu-id="feccd-103">사용자가 MFA (multi-factor authentication)를 사용 하 여 로그인 할 수 없는 경우 확인 해야 할 몇 가지 사항이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="feccd-104">영향을 받는 사용자가 Azure Active Directory 포털에서 차단 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="feccd-105">이 경우 특정 사용자에 대 한 인증 시도가 자동으로 거부 됩니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="feccd-106">이 문서에서 설명 하는 단계에 따라 차단을 해제 하세요.</span><span class="sxs-lookup"><span data-stu-id="feccd-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="feccd-107">사용자가 도움이 되지 않았거나 사용자가 차단 되지 않은 경우 사용자에 대해 MFA를 다시 설정 하 고 등록 프로세스를 다시 진행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="feccd-108">이 문서에 나와 있는 단계를 따르세요.</span><span class="sxs-lookup"><span data-stu-id="feccd-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="feccd-109">처음으로 MFA를 사용 하도록 설정 하는 경우 사용자가 Outlook, Skype 등의 비 브라우저 클라이언트에 로그인 할 수 없는 경우에는 O365 구독에서 ADAL (Active Directory 인증 라이브러리)을 사용 하도록 설정 되지 않은 것입니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="feccd-110">이 경우에는 Exchange Online Powershell에 연결 하 고이 cmdlet을  *set-organizationconfig-OAuth2ClientProfileEnabled: $true* 으로 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="feccd-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>