---
title: 932 AADConnect 업그레이드
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: ff3f74348599788edd8ce0991fe49bb6a54b55af
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36506089"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="99862-102">Azure AD Connect 업그레이드</span><span class="sxs-lookup"><span data-stu-id="99862-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="99862-103">기본적으로 자동 업그레이드는 Azure AD Connect에서 사용 하도록 설정 되어 있으므로 최신 버전을 실행 하 고 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="99862-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="99862-104">자동 업그레이드 설정을 확인 하려면 Azure AD PowerShell에서 **ADSyncAutoUpgrade** cmdlet을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="99862-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="99862-105">Cmdlet은 다음 값 중 하나를 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="99862-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="99862-106">**Enabled**: 자동 업그레이드가 사용 되도록 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="99862-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="99862-107">**사용 안**함: 자동 업그레이드가 사용 하지 않도록 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="99862-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="99862-108">**Suspended**: 시스템이 더 이상 자동 업그레이드를 받을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="99862-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="99862-109">이 값은 구성할 수 없습니다. 시스템에서 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="99862-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="99862-110">자세한 내용은 [자동 업그레이드](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="99862-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="99862-111">최신 버전의 Azure AD Connect를 다운로드 하려면로 [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="99862-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
