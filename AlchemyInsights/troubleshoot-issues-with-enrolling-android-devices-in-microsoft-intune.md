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
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="5b7d2-102">Android 장치 Microsoft Intune에 등록 된 문제를 해결</span><span class="sxs-lookup"><span data-stu-id="5b7d2-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="5b7d2-103">이제 문제를 해결 하려면 아래에 나열 된 리소스를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="5b7d2-104">일부 일반적인 문제 및 해결 방법 단계:</span><span class="sxs-lookup"><span data-stu-id="5b7d2-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="5b7d2-p101">**장치는 회사 포털에서 오류를 암호화 되지 않으므로:** V 7.0로 시작 하 여 특히 Android의 최신 버전에는 장치 완벽 하 게 암호화 되 고 있는지 확인 하려면 시작 암호가 필요 합니다. 일반적인 솔루션 시작 pin을 사용 하도록 설정 하거나 장치를 완벽 하 게 암호화 됩니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-p101">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted. Common solutions are to enable a startup pin or fully encrypt the device. Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span> 
  
 <span data-ttu-id="5b7d2-p102">**Intune 서비스를 사용 하 여 확인 하거나 Intune 관리 콘솔에서 "비정상적인"으로 표시 하려면 장치 실패:** 일부 삼성 4.4 및 5.5 장치 수는 서비스로 확인 하지 않습니다. 이 문제를 3 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-p102">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service. There are 3 possible solutions to this issue:</span></span> 
  
1. <span data-ttu-id="5b7d2-110">수동으로 자동으로 장치 동기화를 시작 하는 Intune 회사 포털 응용 프로그램을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>
    
2. <span data-ttu-id="5b7d2-111">Android 6.0 이상 장치를 업데이트 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-111">Update the device to Android 6.0 or higher.</span></span>
    
3. <span data-ttu-id="5b7d2-p103">Intune 회사 포털 관리에서 삼성 스마트 관리자를 사용 하지 않도록 설정 합니다. 이러한 문제 및 해결 방법에 대 한 자세한 내용이 [은이 문서](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-p103">Disable Samsung Smart Manager from managing the Intune Company Portal. Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span> 
    
 <span data-ttu-id="5b7d2-p104">**사용자 라이선스 유형 잘못 된** 또는 **사용자 이름을 인식 되지 않음 오류:** 사용자가 Intune 또는 EMS 라이선스를 할당 해야 합니다. 이러한 문서를 통해 라이선스를 할당 하려면 검토: Office 관리 센터 또는 Azure 포털 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-p104">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license. Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span> 
  
<span data-ttu-id="5b7d2-116">문제를 해결 하기 위해 추가 리소스:</span><span class="sxs-lookup"><span data-stu-id="5b7d2-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="5b7d2-p105">[Intune 문제를 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 진단 하 고 일반적인 등록 오류를 해결 합니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-p105">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="5b7d2-119">[이 문서](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) 각 등록 및 해결 방법을 방해 하는 일반적인 오류 목록을 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="5b7d2-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span> 
    
3. <span data-ttu-id="5b7d2-120">[Microsoft Intune에서 Android 장치를 등록 하는 방법에 알아봅니다](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="5b7d2-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
    

