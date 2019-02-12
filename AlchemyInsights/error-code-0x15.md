---
title: 오류 코드 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: 원격 데스크톱 서비스 (RDS) 배포에서 Office 2013을 활성화 하는 동안 오류가 수신 중인 경우, 하는 경우에 레지스트리를 편집 하 여 ADAL를 사용 하도록 설정 하는 것이 좋습니다.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29929094"
---
원격 데스크톱 서비스 (RDS) 배포에서 Office 2013을 활성화 하는 동안 오류가 수신 중인 경우, 하는 경우에 레지스트리를 편집 하 여 ADAL를 사용 하도록 설정 하는 것이 좋습니다. 
  
|**레지스트리 키**|**유형**|**값**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |
   
자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)을 참조 하십시오.
  
> [!NOTE]
>  ADAL은 Office 365 ProPlus 및 Office 2016에서 기본적으로 활성화 됩니다. 원격 데스크톱 서비스 (RDS) gt_ 터미널 서비스 이름이 이전에 였습니다. 
  

