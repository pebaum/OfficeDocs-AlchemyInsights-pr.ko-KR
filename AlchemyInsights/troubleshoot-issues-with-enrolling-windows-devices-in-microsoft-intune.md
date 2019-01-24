---
title: Microsoft Intune에서 Windows 장치 등록 된 문제를 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8d19bbd5a5782c7793c87499baf62b2eb7de82ae
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478281"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="af046-102">Microsoft Intune에서 Windows 장치 등록 된 문제를 해결</span><span class="sxs-lookup"><span data-stu-id="af046-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="af046-103">이제 문제를 해결 하려면 아래에 나열 된 리소스를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="af046-104">일부 일반적인 오류 메시지 및 해결 방법 단계:</span><span class="sxs-lookup"><span data-stu-id="af046-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="af046-p101">**소프트웨어를 설치할 수 없으므로 0x80cf4017:** 계정 인증서가 만료 되었습니다. 다시 Intune 관리 콘솔에서 PC 클라이언트 소프트웨어 패키지를 다운로드 합니다. 자세한 내용은이 설명서를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="af046-108">**오류 코드 0x801c0003:** 이 오류는 다음과 같은 시나리오에서 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="af046-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="af046-p102">사용자가 등록 장치 제한 보다 더 많은 장치입니다. [장치를 제거](https://docs.microsoft.com/en-us/intune/devices-wipe) 하거나 [장치 제한을 변경](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions)하려면 다음이 문서를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="af046-p103">"사용자가 장치 Azure AD에 참가할 수 있습니다"는 "none"으로 설정 됩니다. 모두로 설정 하거나 선택 사용자입니다. 자세한 내용은 [이 설명서](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="af046-p104">장치는 이미 다른 사용자가 등록 됩니다. 있는 경우 Azure Intune 콘솔에서 장치를 제거 하거나 다시 시도 하기 전에 장치를 수동으로 등록 해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="af046-p105">장치가 Windows 10 초기화 합니다. 만 Windows 10 Pro, 교육 및 엔터프라이즈 Sku Azure Active Directory에 참가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="af046-118">문제를 해결 하기 위해 추가 리소스:</span><span class="sxs-lookup"><span data-stu-id="af046-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="af046-p106">[Intune 문제를 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 진단 하 고 일반적인 등록 오류를 해결 합니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/en-us/intune/help-desk-operators) 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="af046-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="af046-121">각 등록 및 해결 방법을 방해 하는 일반적인 오류 목록은 이러한 문서를 검토: [문제해결 가이드](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) 및 [문제해결 문서](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)입니다.</span><span class="sxs-lookup"><span data-stu-id="af046-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="af046-122">[Microsoft Intune에서 Windows 장치를 등록 하는 방법에 알아봅니다](https://docs.microsoft.com/en-us/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="af046-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span></span>
  

