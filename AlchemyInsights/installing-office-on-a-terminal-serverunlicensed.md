---
title: 터미널 서버에 office 설치-사용 허가 되지 않음
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 6fc4bd5f6971ca833084a6a8ad6c25b3fdafb8dc
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35381735"
---
# <a name="installing-office-on-a-terminal-server"></a>터미널 서버에 Office 설치

RDS (원격 데스크톱 서비스)를 사용 하 여 Windows Server에 Office 365 ProPlus를 배포 하는 경우 (이전의 터미널 서비스:
  
- Office 365 Enterprise E3 또는 Enterprise e 5와 같은 office 365 ProPlus를 포함 하는 Office 365 요금제가 있어야 합니다. Office 365 Business 및 Office 365 Business Premium 요금제에는 Office 365 ProPlus가 포함 되지 않습니다.

- [공유 컴퓨터 활성화](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)를 사용 하도록 설정 해야 합니다.

Office 365 portal에서 RDS에 Office 365 ProPlus를 설치 하려면 * * *기본 설치 설정을 사용 하는* 경우에는 다음 단계를 수행 합니다.
  
1. 보유 하 고 있는 Office 365 요금제를 확인 합니다. [방법 알아보기](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. 필요한 경우 다른 Office 365 요금제로 전환 합니다. [방법 알아보기](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Office가 다른 Office 365 계획을 사용 하 여 RDS 서버에 이미 설치 되어 있는 경우에는 제거 합니다. 예를 들어 제어판으로 이동 하 여 \> 프로그램을 제거 합니다. 문제가 발생 하는 경우 [Microsoft 지원 및 복구 도우미를](https://aka.ms/SARA-OfficeUninstall-Alchemy) 사용 하 여 제거 합니다.

4. RDS 서버에서 관리자 계정을 사용 하 여 Office 365 포털에 로그인 하 고 [office 365 ProPlus를 설치](https://portal.office.com/OLS/MySoftware.aspx)합니다.

5. Office 설치 후 * * Office 응용 프로그램에 대해 * *를 *열거나 로그온 하지 않습니다* .

6. RDS 서버에서 다음 단계를 수행 하 여 레지스트리를 편집 하 여 공유 컴퓨터 활성화를 사용 하도록 설정 합니다.

1. 화면 왼쪽 아래에 있는 Windows 단추를 마우스 오른쪽 단추로 클릭 하 고 실행을 선택 합니다. 열기 상자에 **regedit**를 입력 하 고 확인을 선택 합니다.

2. 레지스트리 편집기를 사용 하 여 장치를 변경할 수 있는지 묻는 메시지가 표시 되 면 예를 선택 합니다.

3. 레지스트리 편집기에서 HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration. 아래에 설정 1을 사용 하 여 **Sharedcomputerlicensing** 의 문자열 값을 추가 합니다.

7. RDS 서버에서 * * *최종 사용자 * *로 로그인* 하 여 [Office 365 ProPlus에 대해 공유 컴퓨터 활성화가 사용 하도록 설정 되어 있는지 확인](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded)합니다.

Office 배포 도구를 사용 하 여 필수 구성 요소, 설치 지침 및 사용자 지정 설치에 대 한 지침에 대 한 자세한 내용은 [원격 데스크톱 서비스를 사용 하 여 office 365 ProPlus 배포](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services)를 참조 하세요.
  
공유 컴퓨터 활성화와 관련 된 오류를 해결 하려면 [Office 365 ProPlus에 대 한 공유 컴퓨터 활성화의 문제 해결](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus)을 참조 하십시오.
  