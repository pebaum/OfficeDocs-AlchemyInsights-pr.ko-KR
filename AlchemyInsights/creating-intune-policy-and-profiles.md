---
title: Intune 정책 및 프로필 만들기
ms.author: mandia
author: mandia
manager: dougeby
ms.date: 05/07/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 6700005
ms.openlocfilehash: 3fecad7d02b8e3148a3dd774d666fc4ed317204c
ms.sourcegitcommit: 7e2122a7e08525f628986978f396b3a138d2326d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/07/2019
ms.locfileid: "33661740"
---
# <a name="creating-intune-policy-and-profiles"></a><span data-ttu-id="c699e-102">Intune 정책 및 프로필 만들기</span><span class="sxs-lookup"><span data-stu-id="c699e-102">Creating Intune policy and profiles</span></span>

<span data-ttu-id="c699e-103">Intune에서는 다양 한 작업을 수행 하는 정책 및 프로필을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-103">In Intune, you can create policies and profiles that do different things.</span></span>

- <span data-ttu-id="c699e-104">**등록 프로필**: 플랫폼에 따라 디바이스를 미리 구성 하 고, 사용자 선호도를 사용 하며, 다단계 인증을 사용 하는 등의 작업을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-104">**Enrollment profiles**: Preconfigure your devices by platform, enable user affinity, use multi-factor authentication, and more.</span></span> 

  <span data-ttu-id="c699e-105">[장치 등록 이란 무엇](https://docs.microsoft.com/intune/device-enrollment)이며 [Android](https://docs.microsoft.com/intune/android-enroll), [IOS](https://docs.microsoft.com/intune/ios-enroll), [macos](https://docs.microsoft.com/intune/macos-enroll)및 [Windows](https://docs.microsoft.com/intune/windows-enrollment-methods) 에 대 한 등록 프로필을 만드는 것이 좋은 리소스입니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-105">[What is device enrollment](https://docs.microsoft.com/intune/device-enrollment), and create enrollment profiles for [Android](https://docs.microsoft.com/intune/android-enroll), [iOS](https://docs.microsoft.com/intune/ios-enroll), [macOS](https://docs.microsoft.com/intune/macos-enroll), and [Windows](https://docs.microsoft.com/intune/windows-enrollment-methods) are good resources.</span></span>

- <span data-ttu-id="c699e-106">**준수 정책**: 장치에서 준수 해야 하는 규칙 및 설정을 정의 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-106">**Compliance policies**: Define the rules and settings that devices must follow to be compliant.</span></span> <span data-ttu-id="c699e-107">준수 정책을 사용 하 여 장치를 모니터링 하 고 사용자에 게 비 호환성을 알릴 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-107">You can also use compliance policies to monitor devices, and notify users of non-compliance.</span></span> 

  <span data-ttu-id="c699e-108">[장치 준수 정책을](https://docs.microsoft.com/intune/device-compliance-get-started)시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-108">Get started with [device compliance policies](https://docs.microsoft.com/intune/device-compliance-get-started).</span></span>
- <span data-ttu-id="c699e-109">**조건부 액세스 정책**: 입력 한 조건에 따라 조직 리소스를 보호 하도록 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-109">**Conditional access policies**: Help secure organizational resources, depending on conditions that you enter.</span></span> <span data-ttu-id="c699e-110">예를 들어, 호환 되지 않는 장치의 경우 조건부 액세스를 사용 하 여 전자 메일 및 SharePoint에 대 한 액세스를 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-110">For example, for devices that aren't compliant, use conditional access to restrict access to email and SharePoint.</span></span>

  <span data-ttu-id="c699e-111">[조건부 액세스 란 무엇](https://docs.microsoft.com/intune/conditional-access) 이며 [조건부 액세스를 사용 하는 일반적인 방법은](https://docs.microsoft.com/intune/conditional-access-intune-common-ways-use) 시작 하기에 좋은 리소스입니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-111">[What is conditional access](https://docs.microsoft.com/intune/conditional-access) and [common ways to use conditional access](https://docs.microsoft.com/intune/conditional-access-intune-common-ways-use) are good resources to get started.</span></span>

- <span data-ttu-id="c699e-112">**구성 프로필**: 전자 메일 설정을 비롯 하 여 장치에 대 한 기능 및 설정, WiFi 네트워크 추가, 기본 제공 서식 파일 사용, IOS 및 macos 장치 기능 등을 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-112">**Configuration profiles**: Manage features and settings on devices, including email settings, add a WiFi network, use built-in templates, control iOS and macOS device features, and more.</span></span> 

  <span data-ttu-id="c699e-113">[장치 구성 프로필](https://docs.microsoft.com/intune/device-profiles)을 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="c699e-113">Get started at [device configuration profiles](https://docs.microsoft.com/intune/device-profiles).</span></span>

<span data-ttu-id="c699e-114">유용한 링크:</span><span class="sxs-lookup"><span data-stu-id="c699e-114">Helpful links:</span></span>

- [<span data-ttu-id="c699e-115">Intune의 장치 정책 및 프로필에 대 한 일반적인 질문, 문제 및 해결 방법</span><span class="sxs-lookup"><span data-stu-id="c699e-115">Common questions, issues, and resolutions with device policies and profiles in Intune</span></span>](https://docs.microsoft.com/intune/device-profile-troubleshoot)

- [<span data-ttu-id="c699e-116">Intune에서 정책 및 프로필 문제 해결</span><span class="sxs-lookup"><span data-stu-id="c699e-116">Troubleshoot policies and profiles in Intune</span></span>](https://docs.microsoft.com/intune/troubleshoot-policies-in-microsoft-intune)
