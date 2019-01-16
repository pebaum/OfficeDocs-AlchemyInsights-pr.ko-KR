---
title: ADFS 페더레이션 인증서가 만료
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: c608489be8497233d9d4f87ec53649026b823250
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298892"
---
# <a name="adfs-federation-certificate-expiring"></a>ADFS 페더레이션 인증서가 만료

이 문제를 해결 하려면 다음이 단계를 따릅니다.
  
1. (모듈 아직 설치 되지) 하는 경우 Microsoft Azure Active Directory 모듈에 대 한 Windows PowerShell을 컴퓨터에 설치 합니다. 이 작업을 수행 하려면 [Windows PowerShell을 사용 하 여 Azure AD 관리](https://aka.ms/aadposh)로 이동 합니다.
    
2. 단계에 따라는 "시나리오 1: AD FS 토큰 서명 인증서가 만료 되었습니다" [AD FS 페더레이션된 사용자가 Office 365, Azure, 또는 Intune에 로그인 하면에서 "사이트에 액세스 문제가 발생 했습니다" 오류](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)의 섹션입니다.
    
3. [업데이트 또는 Office 365, Azure, 또는 Intune에서 페더레이션된 도메인의 설정을 복구 하는 방법](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)의 단계를 수행 합니다.
    
    페더레이션 인증서를 갱신 하는 방법에 대 한 자세한 내용은 [Office 365와 Azure Active Directory에 대 한 페더레이션 인증서를 갱신을](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs)참조 합니다.
    

