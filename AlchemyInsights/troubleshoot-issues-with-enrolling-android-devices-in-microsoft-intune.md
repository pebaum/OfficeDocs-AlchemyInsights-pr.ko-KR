---
title: Microsoft Intune에서 Android 장치 등록 시 발생 하는 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: bd6d278ebf6cca7fb6e4ac1049deae600b516707
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759626"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="5e469-102">Microsoft Intune에서 Android 장치 등록 시 발생 하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="5e469-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="5e469-103">아래에 나열 된 리소스를 검토 하 여 지금 문제를 해결 하세요.</span><span class="sxs-lookup"><span data-stu-id="5e469-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="5e469-104">몇 가지 일반적인 문제점과 해결 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="5e469-105">**회사 포털에서 장치가 암호화 되지 않음 오류:** 최신 버전의 Android (특히 v 7.0부터 시작 하는 경우)에는 시작 암호를 지정 하 여 장치가 완전히 암호화 되었는지 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="5e469-106">일반적인 해결 방법은 시작 pin을 사용 하거나 장치를 완전히 암호화 하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="5e469-107">자세한 내용을 보려면 [이 문서](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) 를 검토 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5e469-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="5e469-108">**장치가 intune 관리 콘솔에서 intune 서비스와 함께 또는 "비정상"으로 표시 되지 않습니다.** 일부 Samsung 4.4 및 5.5 장치는 서비스에 대 한 검사를 수행할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="5e469-109">이 문제에는 다음과 같은 세 가지 방법을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="5e469-110">Intune 회사 포털 앱을 수동으로 열면 장치 동기화가 자동으로 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="5e469-111">장치를 Android 6.0 이상으로 업데이트 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="5e469-112">Intune 회사 포털 관리에서 Samsung Smart Manager를 사용 하지 않도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="5e469-113">이러한 문제와 해결 방법에 대 한 자세한 내용은 [이 문서](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) 를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5e469-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="5e469-114">**사용자 라이선스 유형 잘못 됨** 또는 **사용자 이름을 인식할 수 없음 오류:** 사용자에 게 Intune 또는 EMS 라이선스를 할당 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="5e469-115">Office 관리 센터 또는 Azure portal을 통해 라이선스를 할당 하려면 다음 문서를 검토 하세요.</span><span class="sxs-lookup"><span data-stu-id="5e469-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="5e469-116">문제를 해결 하는 데 도움이 되는 추가 리소스:</span><span class="sxs-lookup"><span data-stu-id="5e469-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="5e469-117">[Intune 문제 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 일반적인 등록 오류를 진단 하 고 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="5e469-118">자세한 내용을 보려면 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 를 검토 하세요.</span><span class="sxs-lookup"><span data-stu-id="5e469-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="5e469-119">[이 문서](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) 를 검토 하 여 각에 등록 및 확인을 방지 하는 일반적인 오류 목록을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="5e469-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="5e469-120">[Microsoft Intune에서 Android 장치를 등록 하는 방법을 알아봅니다](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="5e469-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
