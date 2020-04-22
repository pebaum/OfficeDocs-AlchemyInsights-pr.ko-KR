---
title: Office 앱에 로그인 하는 문제
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2574"
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763007"
---
# <a name="issues-signing-in-to-office-apps"></a>Office 앱에 로그인 하는 문제

Office 앱의 로그인 문제를 해결 하려면 다음을 시도 합니다.

- Windows 설정을 사용 하 여 영향을 받는 계정을 제외한 모든 작업 계정을 제거 하 여 **회사 또는 학교 액세스**> 합니다.
- Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .<br/>
    **참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다. (예: \Software\Microsoft\Office\16.0\Common\Identity\)
- Office 앱을 열고 **파일** > **계정** > **로그 아웃**을 선택 합니다. 유효한 라이선스가 있는 사용자 계정을 사용 하 여 로그인 합니다. 자세한 내용은 [Office의 계정](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)을 참조하세요.
- Mac의 경우 [Mac용 Office 2016 앱에 로그인 할 수 없습니다](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail)를 참조하세요.
- Office 2013을 사용 하 여 Microsoft 365에 연결 하는 동안 오류가 발생 하면 Office 클라이언트에 대 한 최신 인증을 사용 하도록 설정 합니다.

자세한 내용은 다음을 참조하세요.
- [Microsoft 365, Azure 또는 Intune에 로그인 할 수 없음](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [Office 2016 빌드 16.0.7967 Windows 10에서 업데이트 후 로그인 시 연결 문제가 발생 합니다.](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- ["Office에서 조직의 다른 계정이 이미이 컴퓨터에 로그인 되어 있습니다." 라는 문제가 발생 합니다.](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [ADFS를 사용할 때 Office 최신 인증의 로그인 문제 해결](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)