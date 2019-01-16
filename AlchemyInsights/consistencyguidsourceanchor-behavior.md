---
title: ConsistencyGuid / sourceAnchor 동작
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 80516ed9e15040475a8b65a1af98a1b561704d49
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298772"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor 동작

Azure AD 연결 (버전 1.1.524.0 여운 및) 이제 sourceAnchor 특성으로은 ConsistencyGuid의 사용을 용이 하 게 합니다. 이 기능을 사용할 때 Azure AD 연결을 자동으로 동기화 규칙을 구성 합니다.
  
- 사용자 개체에 대 한 sourceAnchor 특성으로은 ConsistencyGuid를 사용 합니다. ObjectGUID 다른 개체 형식에 사용 됩니다.
    
- 특정에 대 한 온-프레미스 AD 사용자 개체를 해당은 ConsistencyGuid 특성에 채워진, Azure AD 연결 쓰기 objectGUID 값은 ConsistencyGuid 특성 온-프레미스 Active Directory에 백업 되지 않습니다. ConsistencyGuid 특성이 입력 한 후 Azure AD 연결 Azure AD에 개체를 내보냅니다.
    
 **참고:** 한번 온-프레미스 AD 개체는 (즉, AD 커넥터 공간으로 가져오기 및 Metaverse로 프로젝션) Azure AD 연결으로 가져올, 더이상 sourceAnchor 값을 변경할 수 없습니다. 에 대 한 sourceAnchor 값을 지정 하는 온-프레미스 주어진 AD 개체, Azure AD 연결을 가져오면 전에 해당은 ConsistencyGuid 특성을 구성 합니다. 
  
SourceAnchor 및 ConsistencyGuid에 대 한 자세한 내용은 다음 참조: [Azure AD 연결: 개념 디자인](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

