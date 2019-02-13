---
title: 646 AADConnect를 구성 하는 방법
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: dd6d6986b23c8adcc98fe713bacf32fb5bf8b4b6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915585"
---
# <a name="configure-sync-features"></a><span data-ttu-id="d8ea0-102">동기화 기능 구성</span><span class="sxs-lookup"><span data-stu-id="d8ea0-102">Configure sync features</span></span>

<span data-ttu-id="d8ea0-p101">Azure AD 연결에는 기본적으로 사용 하도록 설정 하는 또는 나중에 사용할 수 있는 여러 기능이 포함 됩니다. 일부 기능의 경우 특정 환경에서 추가 구성이 필요 합니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-p101">Azure AD Connect includes several features that are enabled by default, or that you can enable later. Some features require additional configuration in specific environments.</span></span>
  
- <span data-ttu-id="d8ea0-p102">[필터링](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) 제한 개체 Azure AD 동기화 됩니다. 기본적으로 모든 사용자, 연락처, 그룹 및 Windows 10 컴퓨터 계정 동기화 됩니다. 포함 하거나 도메인, Ou, 또는 기타 특성을 기준으로 개체를 제외할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-p102">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD. By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized. You can include or exclude objects based on domains, OUs, or other attributes.</span></span> 
    
- <span data-ttu-id="d8ea0-p103">[암호 해시 동기화](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) Azure AD에 온-프레미스 Active Directory에서 암호 해시를 동기화합니다. 이 통해 한 위치에서 암호 관리 하지만 둘 모두에 동일한 암호를 사용 하 여 온-프레미스 및 클라우드 환경입니다. Active Directory의 신뢰할 수 있는 원본 이기 때문에 자신의 암호 정책을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-p103">[Password hash syncronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD. This allows password management in one location, but use of the same password in both on-premises and cloud environments. Because Active Directory is the authoritative source, you can use your own password policies.</span></span> 
    
- <span data-ttu-id="d8ea0-111">[셀프서비스 암호 재설정 (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) 온-프레미스 암호 정책을 적용 하는 동안 클라우드에서 자신의 암호를 다시 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span> 
    
- <span data-ttu-id="d8ea0-112">조건부 액세스를 위해 사용할 수 있도록 온-프레미스 Active Directory에 다시 쓸 수를 Azure AD에 등록 된 장치를 허용 하는 [장치 쓰기 저장](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) 합니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span> 
    
- <span data-ttu-id="d8ea0-p104">[안함 우연히 삭제](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) 너무 많은 동시 개체 삭제 (동기화 당 500 명이 넘는 개체)를 방지 하려면 기본적으로 활성화 됩니다. 조직의 요구를 충족 하기 위해이 설정을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-p104">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization). You can change this setting to meet the needs of your organization.</span></span> 
    
- <span data-ttu-id="d8ea0-115">Azure AD 연결의 버전은 항상 현재 수 보장 및 [자동 업그레이드](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) express 설치에 기본적으로 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d8ea0-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span> 
    

