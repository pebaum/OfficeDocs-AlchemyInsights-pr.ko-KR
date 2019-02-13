---
title: 932 업그레이드 AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 8038d5ef768d6ee228db7d038ad71d926f4047f3
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29937950"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="68f7e-102">업그레이드 Azure AD 연결</span><span class="sxs-lookup"><span data-stu-id="68f7e-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="68f7e-p101">기본적으로 자동 업그레이드 Azure AD 연결을 확인 하는 것을 최신 버전을 실행 중인에 사용 됩니다. 설정을 확인 하려면 다음 자동 업그레이드, Azure AD PowerShell에서 **Get ADSyncAutoUpgrade** cmdlet을 사용 합니다. Cmdlet은 다음 값 중 하나를 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="68f7e-p101">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version. To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell. The cmdlet will return one of following values:</span></span> 
  
- <span data-ttu-id="68f7e-106">**Enabled**: 자동 업그레이드를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="68f7e-106">**Enabled**: Automatic upgrade is enabled.</span></span> 
    
- <span data-ttu-id="68f7e-107">**사용 하지 않도록 설정**: 자동 업그레이드를 사용 하지 않도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="68f7e-107">**Disabled**: Automatic upgrade is disabled.</span></span> 
    
- <span data-ttu-id="68f7e-p102">**일시 중지 됨**: 시스템 더이상 자동 업그레이드를 받을 수 없습니다. 이 값을 구성할 수 없습니다. 시스템에 의해 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="68f7e-p102">**Suspended**: The system is no longer eligible to receive automatic upgrades. You can't configure this value; it's set by the system.</span></span> 
    
<span data-ttu-id="68f7e-110">자세한 내용은 [자동 업그레이드](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="68f7e-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>
  
<span data-ttu-id="68f7e-111">Azure AD 연결의 최신 버전을 다운로드 하려면로 이동 [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)합니다.</span><span class="sxs-lookup"><span data-stu-id="68f7e-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
  

