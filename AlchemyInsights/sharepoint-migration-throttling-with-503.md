---
title: 503 오류가 발생 한 SharePoint 마이그레이션 제한
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931664"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a>503 오류가 발생 한 SharePoint 마이그레이션 제한

**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다. 이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다. 근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.

Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다. 따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다. 그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.

**SharePoint Online으로 마이그레이션할 때 503 오류 발생**

SharePoint Online으로 마이그레이션하고 503 오류를 수신 하는 것 처럼 보입니다. 가능한 한 빨리 도움이 될 수 있도록 아래 단계를 따르세요. 

1. **지원 센터**, **새 서비스 요청**을 차례로 클릭 합니다.
2. 제목 및 설명에 대해 503을 **사용 하 여 SharePoint 마이그레이션 제한을**입력 합니다.
3. 티켓이 전송 된 후에는 다음 정보를 사용 하 여 업데이트 하세요.
    - 마이그레이션의 남은 양 (예: TBs 수)
    - 마이그레이션 시작 및 종료 날짜
    - 콘텐츠를 마이그레이션하는 위치 (예: SharePoint Server, Box, GDrive, 파일 공유 등)에 대해 설명 합니다.
    - 제한 오류 (예: 시간당 x 스로틀) 수를 예측 하 고 조정이 언제 수행 되는지 확인 합니다.
    - 사용 중인 마이그레이션 도구 (예: SPMT 또는 ShareGate)


