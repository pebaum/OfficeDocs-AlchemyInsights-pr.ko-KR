---
title: 오류 AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7a97d1a5ff352b55833bd457e3220a56130d7e7e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499640"
---
# <a name="error-attributevaluemustbeunique"></a>오류: AttributeValueMustBeUnique

AttributeValueMustBeUnique 오류에 대 한 가장 일반적인 이유는 서로 다른 SourceAnchor (immutableId)와 두 개체의 ProxyAddresses 및/또는 UserPrincipalName 특성에 대 한 같은 값을가지고 있습니다. AttributeValueMustBeUnique 오류를 수정 합니다.
  
1. 복제 된 proxyAddresses, userPrincipalName 또는 오류를 발생 하는 다른 특성 값을 식별할 수 있습니다. 또한 두 (또는 그 이상) 개체는 충돌에 관련 된 식별할 수 있습니다. 동기화를 위한 Azure AD 연결 상태에서 생성 된 보고서를 사용 하는 두 개체를 식별 할 수 있습니다.
    
2. 어떤 개체에 중복 된 값을 설정할 계속 해야 하 고 있는 개체 되어서는 안을 식별 합니다.
    
3. 해당 값이 없는 해야 하는 개체에서 중복 된 값을 제거 합니다. Note 개체에서 원본으로 하는 디렉터리에서 변경을 확인 해야 합니다. 경우에 따라 충돌에 있는 개체 중 하나를 삭제 해야할 수 있습니다.
    
4. 온-프레미스 AD에서에서 변경을 수행한 경우에 고정 가져오기에 대 한 오류에 대 한 변경 내용을 동기화 Azure AD 연결 수 있도록 합니다.
    

