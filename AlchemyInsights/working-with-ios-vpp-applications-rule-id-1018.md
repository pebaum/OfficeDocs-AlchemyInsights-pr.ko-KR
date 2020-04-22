---
title: IOS VPP 응용 프로그램 작업 규칙 Id 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 88a1ef66bf337b3a0094976c122330591aee77ff
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719963"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="27936-102">IOS VPP 응용 프로그램 작업</span><span class="sxs-lookup"><span data-stu-id="27936-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="27936-103">Microsoft intune에서 [볼륨 구매 프로그램을 통해 구매한 iOS 앱을 관리](https://docs.microsoft.com/intune/vpp-apps-ios) 하는 방법에 대 한 자세한 내용은 microsoft Intune에서 Apple Volume purchase program 및 해당 프로그램에 대 한 지원을 활용 하기 위한 기능, 제약 조건 및 단계에 대 한 정보를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="27936-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="27936-104">**일반적인 문제:** "IOS VPP 앱을 내 사용자에 게 할당 했지만 설치 하지 못했습니다."</span><span class="sxs-lookup"><span data-stu-id="27936-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="27936-105">이 문제는 여러 모바일 장치 관리 공급자에서 단일 VPP 토큰을 사용 하는 경우에 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="27936-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="27936-106">Apple의 VPP 토큰은 하나의 공급자에만 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="27936-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="27936-107">여러 공급자와 함께 VPP 토큰을 사용한 경우에는 해당 토큰을 Intune에 다시 업로드 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="27936-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="27936-108">총 설치 수가 라이선스 수를 초과 하는 경우에도 설치가 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="27936-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="27936-109">라이선스에 대 한 사용 현황 보고서를 보려면 **Intune 모바일 앱** \> **앱 라이선스** 페이지로 이동 하세요.</span><span class="sxs-lookup"><span data-stu-id="27936-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="27936-110">사용 중인 라이선스를 회수 하는 방법에 대 한 자세한 내용은 [이 문서를 참조 하세요.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="27936-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
