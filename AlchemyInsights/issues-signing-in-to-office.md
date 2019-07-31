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
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938263"
---
# <a name="blank-sign-in-screen-in-office-apps"></a>Office 앱의 빈 로그인 화면

이 문제를 해결 하려면 다음을 시도 합니다.
- [Windows](https://support.microsoft.com/help/4027667/windows-10-update) 및 [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5)용 최신 업데이트를 설치 합니다.
- Internet explorer 옵션 다시 설정: **도구** > **인터넷 옵션** > **고급** > **재설정 internet explorer 설정** (사용자 지정 설정이 손실 됨)을 확인 한 후 다시 Office에 로그인을 시도 합니다.
- Windows Defender Application Guard (WDAG) 또는 이와 유사한 모든 방화벽 또는 바이러스 백신 프로그램을 사용 하지 않도록 설정 합니다.
    1. 제어판에서 **프로그램**으로 이동한 다음 **Windows 기능 사용 또는 해제**를 선택 합니다.
    2. Windows Defender Application Guard를 사용 하도록 설정 된 경우 사용 하지 않도록 설정 해 봅니다.<br/>
    **참고:** 컴퓨터를 다시 시작 해야 할 수 있습니다.
- BrokerPlugin [AAD WAM 플러그](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) 인이 모든 응용 프로그램 또는 방화벽/바이러스 백신 프로그램에 의해 차단 되지 않는지 확인 합니다.
- Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .<br/>
    **참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다. (예: \Software\Microsoft\Office\16.0\Common\Identity\)

자세한 내용은 [Windows 10의 업데이트 후 Office 2016 빌드 16.0.7967에 로그인 후 연결 문제](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)를 참조 하세요.