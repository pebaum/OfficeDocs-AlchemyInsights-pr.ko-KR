---
title: 902 (개체가 중복으로 인해 동기화 오류)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f576460547110e0e599a9062ae03f690792fe635
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29919878"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>개체가 중복으로 인해 동기화 오류

디렉터리 동기화가 완료 되 면 다음과 같은 오류 메시지 중 하나가 나타날 수 있습니다.
  
- 이 개체와 관련 된 다음과 같은 특성 값 이미 로컬 디렉터리에서 다른 개체와 연결 될 수 있으므로 Microsoft 온라인 서비스에서이 개체를 업데이트할 수 없습니다.
    
- 동일한 프록시 주소와 동기화 된 개체는 Microsoft Online Services 디렉터리에 이미 있습니다.
    
- 이 개체와 관련 된 다음과 같은 특성 값 이미 로컬 디렉터리 서비스에서 다른 개체와 연결 될 수 있으므로이 개체를 업데이트할 수 없음: UserPrincipalName입니다.
    
를 확인 하 고 문제를 해결 하려면 다운로드 하 여 [IdFix DirSync 오류 수정 도구](https://www.microsoft.com/download/details.aspx?id=36832)를 실행 합니다.
  
자세한 내용은 [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o)을 참조 하십시오.
  

