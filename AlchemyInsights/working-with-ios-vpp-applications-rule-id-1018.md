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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478367"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="9ebd5-102">IOS VPP 응용 프로그램 사용 (영문)</span><span class="sxs-lookup"><span data-stu-id="9ebd5-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="9ebd5-103">기능, 제약 조건 및 확인 하기 위한 단계에 대해 자세히 알아보려면 [Microsoft Intune를 사용 하 여 볼륨 구매 프로그램을 통해 구입한 iOS 앱을 관리 하는 방법](https://docs.microsoft.com/intune/vpp-apps-ios) 을 확인 Apple 볼륨 구매 프로그램 및 Microsoft Intune에 대 한 지원을 활용 합니다.</span><span class="sxs-lookup"><span data-stu-id="9ebd5-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span> 
  
 <span data-ttu-id="9ebd5-104">**일반적인 문제:** "내 사용자에 게 iOS VPP 앱을 할당 하 하지만 설치 하지 못했습니다."</span><span class="sxs-lookup"><span data-stu-id="9ebd5-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span> 
  
- <span data-ttu-id="9ebd5-p101">이 문제는 여러 모바일 장치 관리 공급자에서 단일 VPP 토큰을 사용 하는 경우에 발생할 수 있습니다. Apple에서 VPP 토큰에 하나의 공급자만 사용할 수 있습니다. 여러 공급자와 VPP 토큰을 사용 하는 경우 Intune 토큰이 다시 업로드 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9ebd5-p101">This can happen if a single VPP token is used across multiple mobile device management providers. VPP tokens from Apple may only be used with one provider. If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>
    
- <span data-ttu-id="9ebd5-p102">설치 된 총 라이선스 수를 초과 하는 경우에 설치가 실패할 수 있습니다. 라이선스에 대 한 사용 현황 보고서를 보려면 **Intune 모바일 앱** 으로 이동 \> **앱 라이선스** 페이지입니다. 사용 중인 라이선스를 확보 하는 방법을 알아보려면 참조 [이 문서의.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="9ebd5-p102">The installation can also fail if the total number of installations exceed the number of licenses. To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page. To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
    

