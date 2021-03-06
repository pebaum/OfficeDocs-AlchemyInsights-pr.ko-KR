---
title: 1554 Winsock 오류 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766175"
---
# <a name="winsock-error-10061"></a>Winsock 오류 10061

이 오류 코드는 Microsoft에서 대상 호스트와 TCP 소켓 (연결)을 설정 하지 못했음을 의미 합니다. 이 오류의 원인은 대부분 방화벽 구성에 문제가 있을 수 있습니다. 문제를 해결 하려면 다음 설정을 확인 합니다.

- [Microsoft 365 url 및 IP 주소 범위의](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) 정보를 사용 하 여 방화벽 구성을 확인 합니다.

- 오류가 EOP (Exchange Online Protection)와 관련 된 경우에는 [Exchange Online PROTECTION IP 주소](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)에 대 한 변경 사항을 이전에 알렸습니다.

- ISP (인터넷 서비스 공급자)가 포트를 차단 하지 않는지 확인 합니다.

- 커넥터에서 스마트 호스트 및 대상 서버 설정을 확인 합니다.

이러한 방식으로는 *들어오는* 연결을 Microsoft 365에서 차단 하지 않습니다.
