---
title: 작동 하지 않음 미국 은행 계좌 번호에 대 한 DLP 규칙
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 9fd5d4736c5209f85e235dc6a0846f65f1b5f624
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29657005"
---
**데이터 손실 방지 (DLP)** DLP 중요 한 정보 유형 o 365에서 사용 하는 경우에 **미국 은행 계좌 번호** 를 포함 하는 콘텐츠에 대 한 작동 하지 않음에 문제가 있을? 그럴 경우 다음을 확인 콘텐츠 포함 DLP 정책이 원하는 내용을 계산 하는 경우에 필요한 정보입니다. 
  
등 85%의 신뢰 수준으로 구성 된 **미국 은행 계좌 번호** 정책에 대 한 다음 계산 되 및 트리거 규칙에 대 한 검색 해야: 
  
- **[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 자릿수 
    
- **[패턴:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 연속 되는 숫자입니다. 
    
- **[체크섬:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없으면 
    
- **[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP 정책은 이러한 종류의 중요 한 정보를 감지 했습니다 판단 75%에 근접 300 자 내에 있는 경우,: 
    
  - Regex_usa_bank_account_number 정규식 패턴과 일치 하는 콘텐츠를 찾습니다.
    
  - Keyword_usa_Bank_Account의 키워드가 발견되었습니다.
    
    다음 샘플 **미국 은행 계좌 번호** 정책에 대 한 트리거할 예: 검사 계정 78344011 
    
콘텐츠에 대 한 검색 되도록 **미국 은행 계좌 번호** 에 대 한 필요한 것에 대 한 자세한 내용은이 문서의 다음 섹션을 참조 하십시오.: [어떤 중요 한 정보 유형 미국 은행 계좌 번호를 찾습니다](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
다른 종류에 대 한 필요한에 정보에 대 한 다음 문서를 참조를 다른 기본 제공 중요 한 정보 형식을 사용 하 여: [어떤 중요 한 정보 유형 찾습니다](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

