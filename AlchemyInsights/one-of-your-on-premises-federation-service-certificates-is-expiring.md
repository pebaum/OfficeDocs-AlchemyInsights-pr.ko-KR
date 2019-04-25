---
title: 온-프레미스 페더레이션 서비스 인증서 중 하나가 만료 됩니다.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: e1afad0bab317af0f60a6ebda8c3ec8be398e38d
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32419698"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>온-프레미스 페더레이션 서비스 인증서 중 하나가 만료 됩니다.

이 문제를 해결 하려면 다음 단계를 수행 합니다.
  
- 컴퓨터에 Windows PowerShell 용 Microsoft Azure Active Directory 모듈 (모듈을 아직 설치 하지 않은 경우)을 설치 합니다. 이 작업을 수행 하려면 [Graph 용 Azure Active Directory PowerShell](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0) 로 이동 합니다.
    
- [페더레이션 사용자가 Office 365, Azure 또는 Intune에 로그인 하는 경우 ad fs에서](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)"시나리오 1: ad FS 토큰 서명 인증서가 만료 되었습니다." 섹션의 단계를 수행 합니다.
    
- [Office 365, Azure 또는 Intune에서 페더레이션 도메인의 설정을 업데이트 하거나 복구 하는 방법](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 따릅니다.
    
페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [O365 및 Azure AD에 대 한 인증서 갱신](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)을 참조 하세요.
  

