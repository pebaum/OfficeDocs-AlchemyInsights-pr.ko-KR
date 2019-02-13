---
title: Microsoft Intune에서 iOS 장치 등록 된 문제를 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: d28dca4fccf823e627dd179f828ba3b8baf843a6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29924774"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Microsoft Intune에서 iOS 장치 등록 된 문제를 해결

이제 문제를 해결 하려면 아래에 나열 된 리소스를 검토 합니다. 
  
일부 일반적인 오류 메시지 및 해결 방법 단계:
  
- **장치에 도달 하면 첫 문자 장식** 사용자가 등록 장치 제한 보다 더 많은 장치입니다. [장치를 제거](https://docs.microsoft.com/intune/devices-wipe) 하거나 [장치 제한을 변경](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions)하려면 다음이 문서를 검토 합니다.
    
- 이 서비스 **지원 되지 않습니다. 등록 정책 없음:** Apple 푸시 알림 서비스 (한 apn을 사용할)을 구성 하거나 갱신 해야 합니다. 작업을 수행 하는 방법에 대 한 지침이 [은이 문서](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) 검토 합니다. 
    
- **잘못 된 사용자 라이선스 종류 또는 인식 되지 않은 사용자 이름:** 사용자가 Intune 또는 EMS 라이선스를 할당 해야 합니다. 이러한 문서를 통해 라이선스를 할당 하려면 검토: [Office 관리 센터](https://docs.microsoft.com/intune/licenses-assign) 또는 [Azure 포털](https://docs.microsoft.com/azure/active-directory/license-users-groups)합니다.
    
문제를 해결 하기 위해 추가 리소스:
  
1. [Intune 문제를 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 진단 하 고 일반적인 등록 오류를 해결 합니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 검토 합니다. 
    
2. 각 등록 및 해결 방법을 방해 하는 일반적인 오류 목록은 이러한 문서를 검토: [문제해결 가이드](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) 및 [문제해결 문서](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)입니다.
    
3. [Microsoft Intune에서 iOS 장치를 등록 하는 방법에 알아봅니다](https://docs.microsoft.com/intune/ios-enroll).
    

