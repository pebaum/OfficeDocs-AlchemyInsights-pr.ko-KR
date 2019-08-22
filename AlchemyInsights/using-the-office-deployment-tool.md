---
title: Office 배포 도구 사용
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: 874bb7883bca4f062e85963a6828a771cd2dad9b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36531581"
---
# <a name="using-the-office-deployment-tool-odt"></a>ODT (Office 배포 도구) 사용

ODT (Office 배포 도구)를 사용 하 여 Office 365 버전의 Office를 배포 합니다. Office 배포 도구 (setup.exe)는 명령줄에서 실행 되며 구성 XML 파일을 사용 하 여 Office를 배포할 때 적용할 설정을 결정 합니다.
  
1. [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/p/?LinkID=626065)에서 최신 버전의 Office 배포 도구를 다운로드 합니다.

2. [OCT (Office 사용자 지정 도구)](https://config.office.com) 를 사용 하 여 배포 기본 설정을 선택 하 고 구성 XML 파일을 만듭니다. 구성 파일을 내보내 setup.exe가 있는 동일한 폴더에 로컬로 배치 합니다.

    **참고:** Office 설치 문제는 일반적으로 잘못 구성 되거나 malformatted configuration 파일로 인해 발생 합니다. 이러한 문제를 방지 하려면 Office 사용자 지정 도구를 사용 하 여 구성 파일을 만드는 것이 좋습니다. 기존 구성 파일을 Office 사용자 지정 도구로 가져올 수도 있습니다.

3. 관리자 권한 명령 프롬프트에서 setup.exe가 상주 하는 위치로 전환한 다음 다운로드 모드에서 Office 개발 도구를 실행 하 고 방금 저장 한 구성 파일을 지정 합니다. 이 예제에서 구성 파일의 이름은 config.xml입니다.
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. 구성 모드에서 Office 개발 도구를 실행 하 고 구성 파일을 지정 합니다.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **참고:** Office를 설치 하려는 클라이언트 컴퓨터에서이 단계를 실행 해야 하며 해당 컴퓨터에 대 한 로컬 관리자 권한이 있어야 합니다.

Office 365 ProPlus 배포 시나리오에서 Office 개발 도구를 사용 하는 방법에 대 한 자세한 내용은 [Office 배포 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조 하세요. Office 사용자 지정 도구를 사용 하는 방법에 대 한 자세한 내용은 [Office 사용자 지정 도구 개요](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run)를 참조 하세요.
