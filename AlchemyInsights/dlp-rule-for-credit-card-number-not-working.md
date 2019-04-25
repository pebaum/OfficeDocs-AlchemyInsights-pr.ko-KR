---
title: 신용 카드 번호에 대 한 DLP 규칙이 작동 하지 않음
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e1d60c493a27efb7f724d57051e21fad5bd0242f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404512"
---
O365에서 dlp 중요 한 정보 유형을 사용할 때 **신용 카드 번호가** 포함 된 콘텐츠에 대해 **dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까? 이 경우에는 콘텐츠를 평가할 때 DLP 정책을 트리거하는 데 필요한 정보가 포함 되어 있는지 확인 합니다. 예를 들어 신뢰 수준이 85% 인 **신용 카드 정책의** 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다. 
  
- **[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식이 있거나 서식이 없을 수 있는 16 자리 숫자 (dddddddddddddddd)로, Luhn 테스트를 통과 해야 합니다. 
    
- **[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** MasterCard, 검색 카드, jcb, 미국 익스프레스, 선물 카드 및 식사 권을 카드를 포함 하 여 전 세계 모든 주요 브랜드에서 카드를 검색 하는 매우 복잡 하 고 강력한 패턴입니다. 
    
- **[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬 
    
- **[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 85% 확신 합니다. 
    
  - Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.
    
  - 다음 중 하나가 충족됩니다. 
    
  - Keyword_cc_verification의 키워드가 발견되었습니다.
    
  - Keyword_cc_name에서 키워드가 발견 됨
    
  - Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.
    
  - 체크섬 통과
    
    예를 들어 다음은 DLP 신용 카드 번호 정책을 트리거하는 예제입니다.
    
  - <: 4485 3647 3952 7352 
    
  - 만료 날짜: 2/2009
    
콘텐츠의 **신용 카드 번호** 를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 신용 카드 #에 대해 어떤 모양 인지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number) 참조 하십시오.
  
기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.
  

