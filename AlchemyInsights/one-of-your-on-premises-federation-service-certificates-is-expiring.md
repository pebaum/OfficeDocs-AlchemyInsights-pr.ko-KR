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
ms.openlocfilehash: 89a4dd910d43d70e849be19d5f88e281f6d19834
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298632"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>만료 되는 온-프레미스 페더레이션 서비스 인증서 중 하나

이 문제를 해결 하려면 다음이 단계를 따릅니다.
  
- (모듈 아직 설치 되지) 하는 경우 Microsoft Azure Active Directory 모듈에 대 한 Windows PowerShell을 컴퓨터에 설치 합니다. 이 작업을 수행 하려면 [그래프 용 Azure Active Directory PowerShell](https://docs.microsoft.com/en-us/powershell/azure/active-directory/install-adv2?view=azureadps-2.0) 로 이동
    
- 단계에 따라는 "시나리오 1: AD FS 토큰 서명 인증서가 만료 되었습니다" [AD FS 페더레이션된 사용자가 Office 365, Azure, 또는 Intune에 로그인 하면에서 "사이트에 액세스 문제가 발생 했습니다" 오류](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)의 섹션입니다.
    
- T[업데이트 또는 Office 365, Azure, 또는 Intune에서 페더레이션된 도메인의 설정을 복구 하는 방법](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 수행 합니다.
    
페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [O365 및 Azure AD에 대 한 인증서를 갱신](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs)을 참조 하십시오.
  

