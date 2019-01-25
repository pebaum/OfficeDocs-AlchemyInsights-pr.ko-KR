---
title: 작동 하지 않는 신용 카드 번호에 대 한 DLP 규칙
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478719"
---
**데이터 손실 방지 (DLP)** DLP 중요 한 정보 유형 o 365에서 사용 하는 경우에 **신용 카드 번호** 를 포함 하는 콘텐츠에 대 한 작동 하지 않음에 문제가 있을? 그렇다면 콘텐츠 트리거 하는데 필요한 정보를 포함 되어있는지 확인은 계산 하는 경우 DLP 정책입니다. 등 **신용 카드 정책** 85%의 신뢰도 사용 하 여 구성에 대 한 다음 계산 되 및 트리거 규칙에 대 한 검색 해야: 
  
- **[형식:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식을 지정할 수는 16 자리 또는 서식이 지정 되지 않은 (dddddddddddddddd) Luhn 테스트로 전달 해야 합니다. 
    
- **[패턴:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** 모든 주요 브랜드 Visa, Mastercard, 검색 카드, JCB, American Express, gift 카드 및 diner 카드를 포함 하 여 전세계에서 카드를 감지 하는 매우 복잡 하 고 강력한 패턴입니다. 
    
- **[체크섬:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬 
    
- **[정의:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 85%에 근접 300 자 내에 있는 경우,: 
    
  - Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.
    
  - 다음 중 하나가 충족됩니다. 
    
  - Keyword_cc_verification의 키워드가 발견되었습니다.
    
  - Keyword_cc_name의 키워드가 발견되었습니다.
    
  - Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.
    
  - 체크섬이 통과됩니다.
    
    예, 다음 샘플 DLP 신용 카드 번호 정책에 대 한 트리거할:
    
  - Visa: 4485 3647 3952 7352 
    
  - 2/2009 만료 됨:
    
콘텐츠에 대 한 검색 되도록 하려면 **신용 카드 번호** 에 대해 필요한 것에 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하십시오.: [어떤 중요 한 정보 유형 찾도록 신용 카드 #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

