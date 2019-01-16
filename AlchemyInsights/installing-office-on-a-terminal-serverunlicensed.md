---
title: 터미널 서버-사용 허가 되지 않은에서 office를 설치합니다.
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 73d5128b55cae7712c48be9e2d05e558c3ba2e5c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299218"
---
# <a name="installing-office-on-a-terminal-server"></a>터미널 서버에서 Office를 설치합니다.

원격 데스크톱 서비스 (RDS)를 사용 하 여 Windows 서버에서 Office 365 ProPlus 배포, 터미널 서비스를 명명 됨:
  
- Office 365 ProPlus, 예: Office 365 엔터프라이즈 E3 또는 Enterprise e 5를 포함 하는 Office 365 계획이 있어야 합니다. Office 365 비즈니스 및 Office 365 프리미엄 계획은 Office 365 ProPlus을 포함 하지 마십시오.
    
- [공유 컴퓨터 정품 인증](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)을 사용 하도록 설정 해야 합니다.
    
Office 365 포털에서 RDS에 Office 365 ProPlus를 설치 하려는 경우 * * *는 사용 되는 기본 설치 설정* * *, 다음이 단계를 수행 합니다. 
  
1. 있는 어떤 Office 365 계획을 확인 합니다. [설명 어떻게](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)
    
2. 필요한 경우 스위치를 서로 다른 Office 365를 계획 하는 경우. [설명 어떻게](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)
    
3. Office 다른 Office 365 계획을 사용 하 여 RDS 서버에 이미 설치 되어이 제거 합니다. 제어판으로 이동 하 여 등 \> 프로그램을 제거 합니다. 문제를 실행 하는 경우 [Microsoft 기술 지원 서비스 및 복구 도우미](https://aka.ms/SARA-OfficeUninstall-Alchemy) 를 사용 하 여 제거 합니다. 
    
4. RDS 서버에서 관리자 계정 및 [Office 365 ProPlus 설치](https://portal.office.com/OLS/MySoftware.aspx)를 사용 하 여 Office 365 포털에 로그인 합니다.
    
5. Office가 설치 된 후 * * *열거나에 로그인 하지* * * 모든 Office 응용 프로그램으로 합니다. 
    
6. RDS 서버에서 다음이 단계를 수행 하 여 레지스트리를 편집 하 여 공유 컴퓨터 정품 인증을 사용 하도록 설정 합니다.
    
1. 화면의 왼쪽 아래 모서리에 있는 Windows 단추를 마우스 오른쪽 단추로 클릭 하 고 실행을 선택 합니다. 열기 상자에 **regedit**를 입력 한 다음 확인을 선택 합니다. 
    
2. 예를 선택 레지스트리 편집기를 허용 하도록 대화 상자가 나타나면 장치를 변경 해야 합니다.
    
3. 레지스트리 편집기를 찾아 \Office\ClickToRun\Configuration에서 1로 설정 된 **SharedComputerLicensing** 의 문자열 값을 추가 합니다. 
    
7. RDS 서버에서 * * *최종 사용자로 로그인* * * 하 고 [공유 컴퓨터 정품 인증 Office 365 ProPlus에 대 한 사용 하도록 설정 되었는지 확인](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded)합니다.
    
필수 구성 요소, 설치 지침 및 Office 배포 도구를 사용 하 여 사용자 지정된 설치에 대 한 지침에 대 한 자세한 내용은 [Deploy Office 365 ProPlus 원격 데스크톱 서비스를 사용 하 여](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services)을 참조 하십시오.
  
공유 컴퓨터 정품 인증 관련 된 오류를 수정 하려면 [Office 365 ProPlus에 대 한 공유 컴퓨터 정품 인증 문제를 해결을](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus)참조 하십시오.
  

