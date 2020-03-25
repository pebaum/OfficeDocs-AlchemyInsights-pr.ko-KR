---
title: DLP에 사용자 지정 형식이 필요할 수 있음
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932664"
---
# <a name="dlp-might-need-a-custom-type"></a>DLP에 사용자 지정 형식이 필요할 수 있음

**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다. 이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다. 근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.

Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다. 따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다. 그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.

**DLP에는 사용자 지정 정보 유형이 필요할 수 있습니다.**

DLP (데이터 손실 방지) 정책을 사용 하 여 조직에서 중요 한 데이터를 식별 하 고 보호할 수 있습니다. 일부 시나리오에서는 조직의 데이터를 보호 하기 위해 **사용자 지정** 중요 한 정보 유형을 직접 만들어야 할 수도 있습니다.

예를 들어 조직에서 조직의 특정 형식으로 직원 Id 또는 기타 데이터를 식별 하 고 보호 해야 할 수 있습니다. 이 경우 자세한 내용은 다음 문서를 참조 하세요.
  
 **기본 제공 중요한 정보 유형 사용자 지정**
  
기본 제공 중요 한 정보 유형이 몇 가지 수단 만으로 요구 사항을 충족 하는 경우 [에는 기본 제공 중요 한 정보 유형을 사용자 지정할](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type)수 있습니다. 예를 들어 키워드를 추가 또는 제거 하거나, 날짜나 주소와 같은 지원 증거를 추가 하거나 제거할 수 있습니다.
  
 **사용자 지정 중요한 정보 유형 만들기**
  
그러나 서로 다른 유형의 중요 한 정보를 식별 하 고 보호 해야 하는 경우에는 보안 & 준수 센터의 UI에서 [사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) 수 있습니다.
  
**보안 및 준수 센터 PowerShell에서 사용자 지정 중요한 정보 유형 만들기**

마지막으로 UI가 필요한 모든 옵션을 제공 하지 않는 경우 [보안 & 준수 센터 PowerShell에서 사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell)수 있습니다. XML 파일을 시작 하 여 사용 가능한 모든 옵션을 사용할 수 있습니다.
