---
title: Office 배포 도구를 사용 하 여
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: b4ade0f21794a8986aa7a37d783da5fa289488fc
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299304"
---
# <a name="using-the-office-deployment-tool-odt"></a>Office 개발 도구 (ODT)를 사용 하 여

Office 배포 도구 (ODT)를 사용 하 여 Office 365 버전의 Office 배포 합니다. Office 개발 도구 (setup.exe) 명령줄에서 실행 되 고 구성 XML 파일을 사용 하 여 Office를 배포할 때 적용할 설정을 확인 하 합니다.
  
1. [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/p/?LinkID=626065)에서 최신 버전의 Office 배포 도구를 다운로드 합니다.
    
2. [Office 사용자 지정 도구 (OCT)를](https://config.office.com) 사용 하 여 하 여 배포 기본 설정을 선택 하 고 구성 XML 파일을 만듭니다. 구성 파일을 내보내고 setup.exe 상주 하는 동일한 폴더에 대해 로컬로 배치 합니다. 
    
    **참고:** 문제 일반적으로 발생 이유 때문에 잘못 구성 된 office 설치 또는 구성 파일 형식이 틀립니다. 이러한 문제를 방지 하려면 구성 파일을 만들려면 Office 사용자 지정 도구를 사용 하는 것이 좋습니다. Office 사용자 지정 도구에 기존 구성 파일을 가져올 수도 있습니다. 
    
3. 상승된 된 명령 프롬프트에서 setup.exe가 있는 위치를 전환 하 고 Office 배포 도구를 다운로드 모드에서 실행 하 고 방금 저장 구성 파일을 지정 합니다. 이 예제에서는 구성 파일 Configuration.xml 이름이 지정 됩니다.
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Office 배포 도구를 실행에서 모드를 구성 하 고 구성 파일을 지정 합니다.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **참고:** 클라이언트 컴퓨터에 Office를 설치 하려는 하 고 해당 컴퓨터에서 로컬 관리자 권한이 있어야에서이 단계를 실행 해야 합니다. 
    
Office 365 ProPlus 배포 시나리오에 대 한 Office 배포 도구를 사용 하는 방법에 대 한 자세한 내용은, [Office 개발 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)를 참고 하십시오. Office 사용자 지정 도구를 사용 하는 방법에 대 한 자세한 내용은 [Office 사용자 지정 도구 개요](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run)를 참조 하십시오.
  

