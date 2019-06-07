---
title: 646 AADConnect 구성 방법
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 646
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 2dc4ae7d6809c24ce599ac128570e9354c9f2b30
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752567"
---
# <a name="configure-sync-features"></a><span data-ttu-id="ee232-102">동기화 기능 구성</span><span class="sxs-lookup"><span data-stu-id="ee232-102">Configure sync features</span></span>

<span data-ttu-id="ee232-103">Azure AD Connect에는 기본적으로 사용 하도록 설정 되거나 나중에 사용 하도록 설정할 수 있는 몇 가지 기능이 포함 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="ee232-104">일부 기능에는 특정 환경에서 추가 구성을 수행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="ee232-105">[필터링](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) 제한 개체가 Azure AD로 동기화 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="ee232-106">기본적으로 모든 사용자, 연락처, 그룹 및 Windows 10 컴퓨터 계정이 동기화 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="ee232-107">도메인, Ou 또는 기타 특성에 따라 개체를 포함 하거나 제외할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="ee232-108">[암호 해시 동기화](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) 온-프레미스 Active Directory에서 Azure AD로의 암호 해시를 동기화 합니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-108">[Password hash syncronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="ee232-109">이를 통해 한 위치에서 암호를 관리할 수 있지만 온-프레미스 및 클라우드 환경 둘 다에서 동일한 암호를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="ee232-110">Active Directory는 신뢰할 수 있는 원본 이기 때문에 고유한 암호 정책을 사용 해도 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="ee232-111">[SSPR (셀프 서비스 암호 재설정)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) 를 사용 하면 온-프레미스 암호 정책을 적용 하는 동안 사용자가 클라우드에서 자신의 암호를 다시 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="ee232-112">[장치 쓰기 저장](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) 을 사용 하면 Azure AD의 등록 장치를 온-프레미스 Active Directory에 다시 기록 하 여 조건부 액세스에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="ee232-113">[실수로 삭제 방지](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) 기능은 동시에 너무 많은 개체 삭제를 방지 하기 위해 기본적으로 사용 됩니다 (동기화 당 500 개 초과 개체).</span><span class="sxs-lookup"><span data-stu-id="ee232-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="ee232-114">조직의 필요에 맞게이 설정을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="ee232-115">[자동 업그레이드](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) 는 빠른 설치의 경우 기본적으로 사용 하도록 설정 되며, 현재 버전의 Azure AD Connect가 항상 최신 상태를 유지 하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ee232-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>
