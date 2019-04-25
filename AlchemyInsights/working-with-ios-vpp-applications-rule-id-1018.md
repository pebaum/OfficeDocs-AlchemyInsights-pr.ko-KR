---
title: iOS VPP 응용 프로그램 작업 규칙 Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 65b9a727171a7551068717f6327f15e1aa8e6bed
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420490"
---
# <a name="working-with-ios-vpp-applications"></a>iOS VPP 응용 프로그램 작업

microsoft intune에서 [볼륨 구매 프로그램을 통해 구매한 iOS 앱을 관리](https://docs.microsoft.com/intune/vpp-apps-ios) 하는 방법에 대 한 자세한 내용은 microsoft intune에서 Apple volume purchase program 및 해당 프로그램에 대 한 지원을 활용 하기 위한 기능, 제약 조건 및 단계에 대 한 정보를 참조 하세요. 
  
 **일반적인 문제:** "iOS VPP 앱을 내 사용자에 게 할당 했지만 설치 하지 못했습니다." 
  
- 이 문제는 여러 모바일 장치 관리 공급자에서 단일 VPP 토큰을 사용 하는 경우에 발생할 수 있습니다. Apple의 VPP 토큰은 하나의 공급자에만 사용할 수 있습니다. 여러 공급자와 함께 VPP 토큰을 사용한 경우에는 해당 토큰을 Intune에 다시 업로드 해야 합니다.
    
- 총 설치 수가 라이선스 수를 초과 하는 경우에도 설치가 실패할 수 있습니다. 라이선스에 대 한 사용 현황 보고서를 보려면 **Intune 모바일 앱** \> **앱 라이선스** 페이지로 이동 하세요. 사용 중인 라이선스를 회수 하는 방법에 대 한 자세한 내용은 [이 문서를 참조 하세요.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

