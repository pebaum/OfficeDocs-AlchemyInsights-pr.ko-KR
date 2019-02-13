---
title: 미국에 대 한 DLP 규칙 / 작동 하지 않음 영국 여권 번호
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: bb80ef07364a575f6032bb105cff83cd8f95bd63
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29912108"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>DLP-문제가 미국 / 영국 여권 번호

경우에 문제가 있는 **데이터 손실 방지 (DLP)** 콘텐츠를 포함 하는 것에 대 한 작동 하지는 **미국 / 영국 여권 번호** DLP 중요 한 정보 유형 o 365에서 사용 하는 경우? 그럴 경우 다음을 확인 콘텐츠 포함 DLP 정책이 원하는 내용을 계산 하는 경우에 필요한 정보입니다. 
  
예: 프로그램 **미국 / 영국 여권 번호** 75%의 신뢰 수준으로 구성 된 정책, 계산 되 하 고 다음을 트리거하려면 규칙에 대 한 검색 해야 합니다 
  
- **[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 숫자 9 개 
    
- **[패턴:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 연속 되는 숫자 9 개 
    
- **[체크섬:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없으면 
    
- **[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 75%에 근접 300 자 내에 있는 경우,: 
    
  - Func_usa_uk_passport 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.
    
  - Keyword_passport의 키워드가 발견되었습니다.
    
    다음 예제에 대 한 트리거할 예는 **미국 / 영국 여권 번호** 정책: 123456789 미국 여권 번호 
    
미국에 대 한 필요한 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하는 대화 내용에 대 한 검색 되도록 하려면 영국 여권 번호 /: [미국에 대 한 정보를 어떤 중요 한 정보 유형 / 영국 여권 번호](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

