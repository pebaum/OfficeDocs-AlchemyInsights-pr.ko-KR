---
title: Microsoft Intune에서 iOS 장치 등록 시 발생 하는 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 664c18daca5d8e0ad4a88f41db3ff0dbced606e5
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43736164"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Microsoft Intune에서 iOS 장치 등록 시 발생 하는 문제 해결

아래에 나열 된 리소스를 검토 하 여 지금 문제를 해결 하세요. 
  
몇 가지 일반적인 오류 메시지 및 해결 단계:
  
- **장치 Cap에 도달 함** 사용자에 게 장치 제한 보다 많은 디바이스가 등록 되어 있습니다. 이러한 문서를 검토 하 여 [장치를 제거](https://docs.microsoft.com/intune/devices-wipe) 하거나 [장치 제한을 변경](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions)합니다.
    
- **이 서비스는 지원 되지 않습니다. 등록 정책 없음:** APNS (Apple Push Notification Service)를 구성 하거나 갱신 해야 합니다. 이 작업을 수행 하는 방법에 대 한 지침은 [이 문서](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) 를 참조 하십시오. 
    
- **사용자 라이선스 유형이 잘못 되었거나 사용자 이름을 인식할 수 없습니다.** 사용자에 게 Intune 또는 EMS 라이선스를 할당 해야 합니다. [Office 관리 센터](https://docs.microsoft.com/intune/licenses-assign) 또는 [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups)을 통해 라이선스를 할당 하려면 다음 문서를 검토 하세요.
    
문제를 해결 하는 데 도움이 되는 추가 리소스:
  
1. [Intune 문제 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 일반적인 등록 오류를 진단 하 고 해결 합니다. 자세한 내용을 보려면 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 를 검토 하세요. 
    
2. 다음 문서를 검토 하 여 각 [문제 해결 가이드](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) 및 [문서 문제 해결](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)을 방지 하는 일반적인 오류 목록을 확인 합니다.
    
3. [Microsoft Intune에서 iOS 장치를 등록 하는 방법을 알아봅니다](https://docs.microsoft.com/intune/ios-enroll).
    

