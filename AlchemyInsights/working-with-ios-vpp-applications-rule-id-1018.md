---
title: IOS VPP 응용 프로그램 규칙 Id 1018 (영문)
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 5bcfb6dd7222bd102ff2620c19bfb943e7bd9591
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299558"
---
# <a name="working-with-ios-vpp-applications"></a>IOS VPP 응용 프로그램 사용 (영문)

기능, 제약 조건 및 확인 하기 위한 단계에 대해 자세히 알아보려면 [Microsoft Intune를 사용 하 여 볼륨 구매 프로그램을 통해 구입한 iOS 앱을 관리 하는 방법](https://docs.microsoft.com/intune/vpp-apps-ios) 을 확인 Apple 볼륨 구매 프로그램 및 Microsoft Intune에 대 한 지원을 활용 합니다. 
  
 **일반적인 문제:** "내 사용자에 게 iOS VPP 앱을 할당 하 하지만 설치 하지 못했습니다." 
  
- 이 문제는 여러 모바일 장치 관리 공급자에서 단일 VPP 토큰을 사용 하는 경우에 발생할 수 있습니다. Apple에서 VPP 토큰에 하나의 공급자만 사용할 수 있습니다. 여러 공급자와 VPP 토큰을 사용 하는 경우 Intune 토큰이 다시 업로드 해야 합니다.
    
- 설치 된 총 라이선스 수를 초과 하는 경우에 설치가 실패할 수 있습니다. 라이선스에 대 한 사용 현황 보고서를 보려면 **Intune 모바일 앱** 으로 이동 \> **앱 라이선스** 페이지입니다. 사용 중인 라이선스를 확보 하는 방법을 알아보려면 참조 [이 문서의.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

