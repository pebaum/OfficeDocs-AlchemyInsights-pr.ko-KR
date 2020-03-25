---
title: DLP가 예상 대로 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932628"
---
# <a name="dlp-not-working-as-expected"></a>DLP가 예상 대로 작동 하지 않음

**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다. 이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다. 근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.

Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다. 따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다. 그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.

 **DLP 설정**

Office 365에서 **DLP (데이터 손실 방지)** 에 대 한 문제가 예상 대로 작동 하지 않습니까? 이 경우 **dlp 정책이** 올바르게 설정 되어 있고 데이터에 **dlp 정책이** 평가 되는 동안 검색 하는 작업이 포함 되어 있는지 확인 합니다.
  
DLP 정책을 사용 하면 조직의 중요 한 정보를 식별 하 고 보호할 수 있습니다. DLP 정책을 설정 하려면 [여기](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)에서 정보를 사용 합니다.
  
 **DLP 정책에서 찾는 사항**
  
Office 365 보안 및 준수 센터에서 **기본 제공 중요 한 정보 유형을** 사용 하는 경우 DLP 정책은 이러한 중요 한 유형을 검색할 때 특정 패턴 및 요소를 찾습니다.
  
- **기본 제공 중요 한 정보 유형**

    기본 제공 중요 한 유형과 중요 한 유형을 검색할 때 DLP 정책에서 찾는 사항에 대 한 자세한 내용은 [중요 한 정보 유형에서 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)을 참조 하십시오.

- **사용자 지정 중요 한 정보 유형**

    사용자 지정 중요 한 정보 유형을 만들려는 경우에는 사용자 지정 중요 한 [정보](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)유형을 만드는 방법에 대 한 자세한 내용은 다음 문서를 참조 하십시오.

**DLP 정책 테스트**

기본 제공 또는 사용자 지정 중요 한 정보 유형을 사용 하 여 데이터를 테스트 하려면 **분류** > **중요 정보 유형에**서 **테스트 유형** 옵션을 사용 합니다. 자세한 내용은 [사용자 지정 중요 한 정보 유형 테스트](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center)를 참조 하세요.

 **보고서**
  
- DLP 보고서를 사용 하 여 중요 한 데이터를 파악 [합니다.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)

- 이벤트에 대 한 구체적인 세부 정보를 [문제 보고서](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)와 함께 참조 하십시오.
