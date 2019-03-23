---
title: 1554 Winsock 오류 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772447"
---
# <a name="winsock-error-10061"></a>Winsock 오류 10061

이 오류 코드는 Office 365에서 대상 호스트와의 TCP 소켓 (연결)을 설정할 수 없음을 의미 합니다. 이 오류의 원인은 대부분 방화벽 구성에 문제가 있을 수 있습니다. 문제를 해결 하려면 다음 설정을 확인 합니다.
  
- [Office 365 url 및 IP 주소 범위](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) 에 포함 된 정보로 방화벽 구성 확인
    
- 오류가 EOP (exchange online protection)와 관련 된 경우에는 [exchange online protection IP 주소](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)에 대 한 변경 사항을 이전에 알렸습니다.
    
- ISP (인터넷 서비스 공급자)가 포트를 차단 하지 않는지 확인 합니다.
    
- 커넥터에서 스마트 호스트 및 대상 서버 설정을 확인 합니다.
    
Office 365에서는 이러한 방식으로 *들어오는* 연결을 차단 하지 않습니다. 
  

