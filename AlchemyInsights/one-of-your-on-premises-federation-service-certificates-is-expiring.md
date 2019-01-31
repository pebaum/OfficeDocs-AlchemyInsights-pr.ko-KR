---
title: 만료 되는 온-프레미스 페더레이션 서비스 인증서 중 하나
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 9e2e1a1dd2993b2a02b4405db8a707b23ff4af16
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29658913"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="a7cc3-102">만료 되는 온-프레미스 페더레이션 서비스 인증서 중 하나</span><span class="sxs-lookup"><span data-stu-id="a7cc3-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="a7cc3-103">이 문제를 해결 하려면 다음이 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="a7cc3-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="a7cc3-p101">(모듈 아직 설치 되지) 하는 경우 Microsoft Azure Active Directory 모듈에 대 한 Windows PowerShell을 컴퓨터에 설치 합니다. 이 작업을 수행 하려면 [그래프 용 Azure Active Directory PowerShell](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0) 로 이동</span><span class="sxs-lookup"><span data-stu-id="a7cc3-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="a7cc3-106">단계에 따라는 "시나리오 1: AD FS 토큰 서명 인증서가 만료 되었습니다" [AD FS 페더레이션된 사용자가 Office 365, Azure, 또는 Intune에 로그인 하면에서 "사이트에 액세스 문제가 발생 했습니다" 오류](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)의 섹션입니다.</span><span class="sxs-lookup"><span data-stu-id="a7cc3-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="a7cc3-107">T[업데이트 또는 Office 365, Azure, 또는 Intune에서 페더레이션된 도메인의 설정을 복구 하는 방법](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="a7cc3-107">Follow the steps in t[How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="a7cc3-108">페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [O365 및 Azure AD에 대 한 인증서를 갱신](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="a7cc3-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

