---
title: 암호 동기화 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 165e0ff4b2136b727450946d2c47756ebee7d393
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353111"
---
# <a name="troubleshoot-password-synchronization"></a>암호 동기화 문제 해결

Azure AD Connect 버전 1.1.614.0 이상으로 암호가 동기화 되지 않는 문제를 해결 하려면 다음을 수행 합니다.
  
1. **관리자 권한으로 실행** 옵션을 사용 하 여 Azure AD Connect 서버에서 새 Windows PowerShell 세션을 엽니다.

2. **ExecutionPolicy RemoteSigned** 또는 **ExecutionPolicy 제한이**없는 경우 실행 합니다.

3. Azure AD Connect 마법사를 시작 합니다.

4. **추가 작업** 페이지로 이동 하 여 **문제 해결**을 선택한 후 **다음**을 클릭 합니다.

5. 문제 해결 페이지에서 **시작을 클릭 하 여 PowerShell에서 문제 해결** 메뉴를 시작 합니다.

6. 주 메뉴에서 **암호 동기화 문제 해결**을 선택 합니다.

7. 하위 메뉴에서 **암호 동기화가 전혀 작동 하지**않습니다 .를 선택 합니다.

**문제 해결 작업 결과 이해**
  
문제 해결 작업에서는 다음 검사를 수행 합니다.
  
- Azure AD 테 넌 트에 대해 암호 동기화 기능이 사용 하도록 설정 되어 있는지 확인 합니다.

- Azure AD Connect 서버가 준비 모드에 있지 않은지 확인 합니다.

- 기존 온-프레미스 Active Directory 커넥터 (기존 Active Directory 포리스트에 해당)에 대해 다음을 수행 합니다.

- 
  - 암호 동기화 기능이 사용 하도록 설정 되어 있는지 확인 합니다.

  - Windows 응용 프로그램 이벤트 로그에서 암호 동기화 하트 비트 이벤트를 검색 합니다.

  - 온-프레미스 Active Directory 커넥터 아래의 각 Active Directory 도메인에 대해 다음을 수행 합니다.

  - Azure AD Connect 서버에서 도메인에 연결할 수 있는지 확인 합니다.

  - 온-프레미스 Active Directory 커넥터에서 사용 하는 AD DS (Active Directory 도메인 서비스) 계정이 암호 동기화에 필요한 올바른 사용자 이름, 암호 및 사용 권한을가지고 있는지 확인 합니다.

암호 동기화 문제 해결에 대 한 자세한 내용은 [AZURE AD Connect sync를 사용한 암호 동기화 문제 해결](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization)을 참조 하세요.
  