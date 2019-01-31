---
title: 암호 동기화 문제를 해결합니다
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
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 589820c945fb20f00431655f9f53196e740bb38f
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29655817"
---
# <a name="troubleshoot-password-synchronization"></a>암호 동기화 문제를 해결합니다

문제를 해결 하려면 없는 암호는 Azure AD 연결 버전 1.1.614.0와 동기화 또는 이상:
  
1. **관리자 권한으로 실행** 옵션을 사용 하 여 Azure AD 연결 서버에서 새 Windows PowerShell 세션을 엽니다. 
    
2. **Set-executionpolicy RemoteSigned** 또는 **Set-executionpolicy 무제한**를 실행 합니다. 
    
3. Azure AD 연결 마법사를 시작 합니다.
    
4. 이동은 * * 추가 작업 * * 페이지, * * Troubleshoot * *, **다음**을 클릭 하 고 합니다. 
    
5. 문제해결 페이지 PowerShell에서 **해결할 수 있습니다.를 시작 하려면 실행** 메뉴를 클릭 합니다. 
    
6. 주 메뉴에서 **문제를 해결 하는 암호 동기화**를 선택 합니다. 
    
7. 하위 메뉴에서 **암호 동기화 전혀 작동 하지 않습니다.** 를 선택 합니다. 
    
 **문제 해결 작업의 결과 이해**
  
문제해결 작업 다음 확인을 수행합니다.
  
- 암호 동기화 기능 Azure AD 테 넌 트에 대해 사용 하도록 설정 되었는지 확인 합니다.
    
- Azure AD 연결 서버 준비 모드에 있지 않음을 유효성을 검사 합니다.
    
- 각 커넥터에 대해 기존 온-프레미스 Active Directory (하는 기존 Active Directory 포리스트에 해당).
    
- 
  - 암호 동기화 기능을 사용 하도록 설정 되었는지 확인 합니다.
    
  - Windows 응용 프로그램 이벤트 로그에서 암호 동기화 하트 비트 이벤트를 검색합니다.
    
  - 온-프레미스 Active Directory 커넥터에서 각 Active Directory 도메인:
    
  - 도메인에서 Azure AD 연결 서버에서 연결할 수 있는지 확인 합니다.
    
  - 온-프레미스 Active Directory 커넥터를 사용 하는 Active Directory 도메인 서비스 (AD DS) 계정에 올바른 사용자 이름, 암호 및 암호 동기화를 위해 필요한 사용 권한 있는지 확인 합니다.
    
암호 동기화 문제를 해결 하는 자세한 도움말을 [Azure AD 연결 동기화를 사용 하 여 해결 암호 동기화](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization)를 참조 하십시오.
  

