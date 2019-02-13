---
title: ADFS 페더레이션 인증서가 만료
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 55529265d2356a911624026107fb639f93e29abd
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29925386"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="8f390-102">ADFS 페더레이션 인증서가 만료</span><span class="sxs-lookup"><span data-stu-id="8f390-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="8f390-103">이 문제를 해결 하려면 다음이 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="8f390-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="8f390-p101">(모듈 아직 설치 되지) 하는 경우 Microsoft Azure Active Directory 모듈에 대 한 Windows PowerShell을 컴퓨터에 설치 합니다. 이 작업을 수행 하려면 [Windows PowerShell을 사용 하 여 Azure AD 관리](https://aka.ms/aadposh)로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="8f390-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>
    
2. <span data-ttu-id="8f390-106">단계에 따라는 "시나리오 1: AD FS 토큰 서명 인증서가 만료 되었습니다" [AD FS 페더레이션된 사용자가 Office 365, Azure, 또는 Intune에 로그인 하면에서 "사이트에 액세스 문제가 발생 했습니다" 오류](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)의 섹션입니다.</span><span class="sxs-lookup"><span data-stu-id="8f390-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
3. <span data-ttu-id="8f390-107">[업데이트 또는 Office 365, Azure, 또는 Intune에서 페더레이션된 도메인의 설정을 복구 하는 방법](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="8f390-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
    <span data-ttu-id="8f390-108">페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [Office 365와 Azure Active Directory에 대 한 페더레이션 인증서를 갱신을](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)참조 합니다.</span><span class="sxs-lookup"><span data-stu-id="8f390-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
    

