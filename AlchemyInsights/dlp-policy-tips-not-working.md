---
title: DLP 정책 팁이 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932592"
---
# <a name="dlp-policy-tip-issues"></a>DLP 정책 팁 문제

**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다. 이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다. 근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.

Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다. 따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다. 그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.

**DLP 정책 팁**

**DLP 정책을**사용 하는 경우 사용자에 게 **정책 팁**을 사용 하 여 정책 위반에 대 한 알림을 받을 수 있습니다. 관리자는 DLP 정책을 테스트 하는 동안 또는 정책이 전체 적용 모드일 때 표시 되도록 정책 팁을 구성할 수 있습니다.
  
보안 및 준수 센터의 전체 적용 모드에서 DLP 정책에 대 한 정책 팁을 구성 하려면 다음을 수행 합니다.
  
- [여기에 나와](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)있는 단계를 사용 하 여 DLP 규칙에 대 한 정책 팁을 **사용 하도록 설정** 해야 합니다.

- 이 [문서에서](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)설명 하는 규칙을 트리거하는 **데 필요한** 내용과 **콘텐츠가 일치** 하는지 확인 합니다.

- OWA 및 Outlook 둘 다에 정책 팁이 표시 됩니다. 그러나 **Outlook 2013 이상 버전**을 사용 하는 경우 정책 팁은 특정 조건에만 표시 됩니다. 여기에는 다음과 같은 조건이 나열 됩니다. [정책 팁 표시를 위해 Outlook 2013 이상에 대해 지원 되는 조건](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)

DLP 정책 팁에 대 한 자세한 내용은 다음을 참조 하십시오. [dlp 정책에 대 한 정책 팁 표시](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
  