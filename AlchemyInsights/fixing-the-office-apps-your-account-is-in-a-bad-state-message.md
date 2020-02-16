---
title: 계정이 잘못 된 상태 메시지에 있는 Office 앱 수정
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969583"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Office 앱 문제 해결 "계정이 잘못 된 상태입니다." 오류

이 오류를 해결 하려면 영향을 받는 컴퓨터에서 다음 옵션을 사용해 보십시오.

- Office 앱을 열고 모든 계정에서 **파일** > **계정** > **로그 아웃**을 선택 합니다. 유효한 라이선스가 있는 사용자 계정을 사용 하 여 다시 로그인 합니다. 자세한 내용은 [Office의 계정을](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)참조 하세요.
- Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .<br>
  **참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다. 예를 들어 \Software\Microsoft\Office\16.0\Common\Identity\
- 영향을 받는 컴퓨터에서 다음 단계를 사용 하 여 EnableADAL = 0을 설정 합니다.  
     1. Windows 단추를 마우스 오른쪽 단추로 클릭 하 고 **실행**을 선택 합니다. **열기** 상자에 **regedit**를 입력 하 고 **확인**을 선택 합니다.
     2. 레지스트리 편집기를 사용 하 여 장치를 변경할 수 있는지 묻는 메시지가 표시 되 면 **예** 를 선택 합니다.
    3. 레지스트리 편집기에서 HKEY_CURRENT_USER \Software\Microsoft\Office\16.0\Common\Identity.에서 설정이 0 인 DWORD 값 EnableADAL를 추가 합니다.
- Office 2013을 사용 하 여 Office 365에 연결 하는 동안 오류가 발생 하는 경우 Office 클라이언트에 대 한 [최신 인증을 사용 하도록 설정](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) 합니다.

자세한 내용은 [Office 365, Azure 또는 Intune에 로그인 할 수 없는 비 브라우저 앱 문제를 해결](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)하는 방법을 참조 하세요.

