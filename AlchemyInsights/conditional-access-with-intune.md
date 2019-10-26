---
title: Intune을 사용한 조건부 액세스
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36505000"
---
# <a name="conditional-access-with-intune"></a>Intune을 사용한 조건부 액세스

Intune을 사용 하 여 **조건부 액세스** 를 사용 하려면 3 단계가 필요 합니다. 
  
- 보호할 리소스와 해당 리소스에 액세스 하기 위해 충족 해야 하는 조건을 정의 하는 **조건부 액세스 정책을** 만듭니다. 예를 들어 회사 전자 메일에 액세스 하기 전에 장치가 규격 이어야 합니다. 
    
- 장치가 호환 되는 것으로 간주 되기 전에 충족 해야 하는 설정을 정의 하는 **준수 정책을** 만듭니다. 예를 들어 장치에는 호환 되는 것으로 간주 되기 전에 6 자리 이상의 pin이 있어야 합니다. 
    
- **준수 정책과** **조건부 액세스 정책이** 원하는 사용자 그룹을 대상으로 하도록 보장 합니다. 이를 위해서는 Azure Active Directory에서 특정 사용자 그룹을 만들어야 할 수 있습니다. 
    
자세한 내용은 다음을 참조 하십시오.
  
- [조건부 액세스 모범 사례](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [조건부 액세스 시작](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

