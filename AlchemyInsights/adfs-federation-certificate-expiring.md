---
title: ADFS 페더레이션 인증서가 만료 됨
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 518261787b1b0df99ee7b3dc3e51dec70e4373bc
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30755160"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="c2329-102">ADFS 페더레이션 인증서가 만료 됨</span><span class="sxs-lookup"><span data-stu-id="c2329-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="c2329-103">이 문제를 해결 하려면 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="c2329-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="c2329-104">컴퓨터에 Windows PowerShell 용 Microsoft Azure Active Directory 모듈 (모듈을 아직 설치 하지 않은 경우)을 설치 합니다.</span><span class="sxs-lookup"><span data-stu-id="c2329-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="c2329-105">이렇게 하려면 [Windows PowerShell을 사용 하 여 Azure AD 관리](https://aka.ms/aadposh)로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="c2329-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>
    
2. <span data-ttu-id="c2329-106">[페더레이션 사용자가 Office 365, Azure 또는 Intune에 로그인 하는 경우 ad fs에서](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)"시나리오 1: ad FS 토큰 서명 인증서가 만료 되었습니다." 섹션의 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="c2329-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
3. <span data-ttu-id="c2329-107">[Office 365, Azure 또는 Intune에서 페더레이션 도메인의 설정을 업데이트 하거나 복구 하는 방법](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="c2329-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
    <span data-ttu-id="c2329-108">페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [갱신 페더레이션 인증서 Office 365 및 Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c2329-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
    

