---
title: 작동 하지 않는 SSN에 대 한 DLP 규칙
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: b92d122b774d97cd2e44cc0880dc5001065b57cc
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298630"
---
**데이터 손실 방지 (DLP)** Office 365의 중요 한 정보 유형을 사용 하는 경우에 **사회보장 번호 (SSN)를** 포함 하는 콘텐츠에 대 한 작동 하지 않음에 문제가 있을? 그렇다면 콘텐츠 DLP 정책을 찾고이 기능에 대 한 필요한 정보를 포함 되어있는지 확인 합니다. 
  
등 85%의 신뢰 수준으로 구성 하는 SSN 정책에 대 한 다음 계산 되 및 트리거 규칙에 대 한 검색 해야:
  
- 서식이 지정 된 또는 서식이 지정 되지 않은 패턴에 있을 수 있는 **[형식:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 자리 
    
- **[패턴:](https://msconnect.microsoft.com/https:/docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** 4 개의 함수 SSNs 4 개의 서로 다른 패턴에 나타나는지 확인합니다. 
    
  - Func_ssn p r e 2011 강력한 서식이 적용 된 대시 또는 공백 (ddd-dd-dddd OR ddd dd dddd)으로 포맷 된 SSNs 발견
    
  - Func_unformatted_ssn p r e 2011 강력한 서식이 지정 된 연속 되는 숫자 9 개 (ddddddddd)로 서식이 지정 된 되지 않은 SSNs 발견
    
  - Func_randomized_formatted_ssn 대시 또는 공백 (ddd-dd-dddd OR ddd dd dddd)로 서식이 지정 된 게시물 2011 SSNs 발견
    
  - Func_randomized_unformatted_ssn 연속 되는 숫자 9 개 (ddddddddd)로 서식이 지정 된 되지 않은 게시물 2011 SSNs 발견
    
- **[체크섬:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** 아니요, 체크섬이 없으면 
    
- **[정의:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 85%에 근접 300 자 내에 있는 경우,: 
    
  - 다음은 [함수 Func_ssn은](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) 패턴과 일치 하는 콘텐츠를 찾습니다. 
    
  - [Keyword_ssn](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) 에서 키워드를 발견 됩니다. 키워드의 예를 포함: *주민등록, 주민등록 #, Soc 초, SSN* 합니다. 다음 샘플 DLP SSN 정책에 대 한 트리거할 예: **SSN: 489-36-8350**
    
콘텐츠에 대 한 검색 되도록 하려면 SSNs에 대 한 필요한 것에 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하십시오.: [어떤 중요 한 정보 유형 SSNs 찾습니다](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

