---
title: DKIM 설정 문제 해결
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765197"
---
# <a name="fix-dkim-setup-issues"></a>DKIM 설정 문제 해결

사용자 지정 도메인에 대해 DKIM을 사용 하도록 설정 하는 데 문제가 발생 하면 다음 단계를 수행 합니다.

- 대부분의 DKIM 설정 문제는 잘못 된 DNS 레코드와 관련이 있습니다. TXT 레코드가**아닌** DKIM CNAME 레코드의 서식이 올바르게 지정 되었는지 확인 합니다. 자세한 내용은이 [항목](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365)을 참조 하십시오.

- 도메인의 DNS 호스팅 서비스 (대개 도메인 등록자)에서 DKIM DNS 레코드를 만들거나 업데이트 한 후에는 DNS 레코드가 전파 될 때까지 기다립니다.

- 관리 센터 \<에서 DKIM DNS 레코드를 만들 수 없는 경우 customdomain\> 을 사용자 지정 도메인 (예: `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`Contoso.com)으로 바꾸고 [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell)에서이 명령을 실행할 수 있습니다.
