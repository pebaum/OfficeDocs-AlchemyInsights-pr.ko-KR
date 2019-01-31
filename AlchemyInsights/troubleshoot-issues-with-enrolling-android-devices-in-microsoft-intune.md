---
title: Android 장치 Microsoft Intune에 등록 된 문제를 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 6b26b2d77bceb063090986ff4e20bc4a56bb1242
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29655889"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Android 장치 Microsoft Intune에 등록 된 문제를 해결

이제 문제를 해결 하려면 아래에 나열 된 리소스를 검토 합니다.
  
일부 일반적인 문제 및 해결 방법 단계:
  
 **장치는 회사 포털에서 오류를 암호화 되지 않으므로:** V 7.0로 시작 하 여 특히 Android의 최신 버전에는 장치 완벽 하 게 암호화 되 고 있는지 확인 하려면 시작 암호가 필요 합니다. 일반적인 솔루션 시작 pin을 사용 하도록 설정 하거나 장치를 완벽 하 게 암호화 됩니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) 검토 합니다. 
  
 **Intune 서비스를 사용 하 여 확인 하거나 Intune 관리 콘솔에서 "비정상적인"으로 표시 하려면 장치 실패:** 일부 삼성 4.4 및 5.5 장치 수는 서비스로 확인 하지 않습니다. 이 문제를 3 해결할 수 있습니다. 
  
1. 수동으로 자동으로 장치 동기화를 시작 하는 Intune 회사 포털 응용 프로그램을 엽니다.
    
2. Android 6.0 이상 장치를 업데이트 합니다.
    
3. Intune 회사 포털 관리에서 삼성 스마트 관리자를 사용 하지 않도록 설정 합니다. 이러한 문제 및 해결 방법에 대 한 자세한 내용이 [은이 문서](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) 검토 합니다. 
    
 **사용자 라이선스 유형 잘못 된** 또는 **사용자 이름을 인식 되지 않음 오류:** 사용자가 Intune 또는 EMS 라이선스를 할당 해야 합니다. 이러한 문서를 통해 라이선스를 할당 하려면 검토: Office 관리 센터 또는 Azure 포털 합니다. 
  
문제를 해결 하기 위해 추가 리소스:
  
1. [Intune 문제를 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 진단 하 고 일반적인 등록 오류를 해결 합니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 검토 합니다. 
    
2. [이 문서](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) 각 등록 및 해결 방법을 방해 하는 일반적인 오류 목록을 검토 합니다. 
    
3. [Microsoft Intune에서 Android 장치를 등록 하는 방법에 알아봅니다](https://docs.microsoft.com/intune/android-enroll).
    

