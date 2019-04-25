---
title: 932 AADConnect 업그레이드
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 932
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 8ffa8f64019077034bc4fad61d1d843849c42898
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32389710"
---
# <a name="upgrade-azure-ad-connect"></a>Azure AD Connect 업그레이드

기본적으로 자동 업그레이드는 Azure AD Connect에서 사용 하도록 설정 되어 있으므로 최신 버전을 실행 하 고 있는지 확인할 수 있습니다. 자동 업그레이드 설정을 확인 하려면 Azure AD PowerShell에서 **ADSyncAutoUpgrade** cmdlet을 사용 합니다. cmdlet은 다음 값 중 하나를 반환 합니다. 

- **Enabled**: 자동 업그레이드가 사용 되도록 설정 됩니다.

- **사용 안**함: 자동 업그레이드가 사용 하지 않도록 설정 됩니다.

- **Suspended**: 시스템이 더 이상 자동 업그레이드를 받을 수 없습니다. 이 값은 구성할 수 없습니다. 시스템에서 설정 합니다. 

자세한 내용은 [자동 업그레이드](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade)를 참조 하세요.

최신 버전의 Azure AD Connect를 다운로드 하려면로 [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)이동 합니다.
