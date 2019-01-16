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
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="6c643-102">Office 개발 도구 (ODT)를 사용 하 여</span><span class="sxs-lookup"><span data-stu-id="6c643-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="6c643-p101">Office 배포 도구 (ODT)를 사용 하 여 Office 365 버전의 Office 배포 합니다. Office 개발 도구 (setup.exe) 명령줄에서 실행 되 고 구성 XML 파일을 사용 하 여 Office를 배포할 때 적용할 설정을 확인 하 합니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-p101">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office. The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="6c643-105">[Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/p/?LinkID=626065)에서 최신 버전의 Office 배포 도구를 다운로드 합니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
    
2. <span data-ttu-id="6c643-p102">[Office 사용자 지정 도구 (OCT)를](https://config.office.com) 사용 하 여 하 여 배포 기본 설정을 선택 하 고 구성 XML 파일을 만듭니다. 구성 파일을 내보내고 setup.exe 상주 하는 동일한 폴더에 대해 로컬로 배치 합니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-p102">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file. Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span> 
    
    <span data-ttu-id="6c643-p103">**참고:** 문제 일반적으로 발생 이유 때문에 잘못 구성 된 office 설치 또는 구성 파일 형식이 틀립니다. 이러한 문제를 방지 하려면 구성 파일을 만들려면 Office 사용자 지정 도구를 사용 하는 것이 좋습니다. Office 사용자 지정 도구에 기존 구성 파일을 가져올 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-p103">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files. To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file. You can also import existing configuration files into the Office Customization Tool.</span></span> 
    
3. <span data-ttu-id="6c643-p104">상승된 된 명령 프롬프트에서 setup.exe가 있는 위치를 전환 하 고 Office 배포 도구를 다운로드 모드에서 실행 하 고 방금 저장 구성 파일을 지정 합니다. 이 예제에서는 구성 파일 Configuration.xml 이름이 지정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-p104">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved. In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="6c643-113">Office 배포 도구를 실행에서 모드를 구성 하 고 구성 파일을 지정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="6c643-114">**참고:** 클라이언트 컴퓨터에 Office를 설치 하려는 하 고 해당 컴퓨터에서 로컬 관리자 권한이 있어야에서이 단계를 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6c643-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span> 
    
<span data-ttu-id="6c643-p105">Office 365 ProPlus 배포 시나리오에 대 한 Office 배포 도구를 사용 하는 방법에 대 한 자세한 내용은, [Office 개발 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)를 참고 하십시오. Office 사용자 지정 도구를 사용 하는 방법에 대 한 자세한 내용은 [Office 사용자 지정 도구 개요](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="6c643-p105">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
  

