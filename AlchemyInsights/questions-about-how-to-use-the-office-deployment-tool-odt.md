---
title: Office 배포 도구 (ODT)를 사용 하는 방법에 대 한 질문
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: c16b7ac7d79794307fa33ed1039305ed5b842cf6
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298459"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="a3a0a-102">Office 배포 도구 (ODT)를 사용 하는 방법에 대 한 질문</span><span class="sxs-lookup"><span data-stu-id="a3a0a-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="a3a0a-103">Office 배포 도구를 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/p/?LinkID=626065)에서 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="a3a0a-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="a3a0a-104">파일을 다운로드한 후에 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="a3a0a-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="a3a0a-105">**제외 하거나 클라이언트 컴퓨터에서 Office 365 ProPlus 제품을 제거 합니다.**</span><span class="sxs-lookup"><span data-stu-id="a3a0a-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="a3a0a-p101">Office 365 ProPlus를 설치할 경우 특정 제품을 제외할 수 있습니다. 이렇게 하려면 ODT를 사용하여 Office를 설치하기 위한 단계를 수행하되 구성 파일에 ExcludeApp 요소를 포함합니다. 예를 들어 이 구성 파일은 Publisher를 제외한 모든 Office 365 ProPlus 제품을 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="a3a0a-p101">When installing Office 365 ProPlus, you can exclude specific products. To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file. For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="a3a0a-109">Office 배포 도구 개요</span><span class="sxs-lookup"><span data-stu-id="a3a0a-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

