---
title: 1332 OWA-받은 편지함 규칙 실행 중인 아닌 사서함에 대 한
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 0d3b7ce3d6b32d94a012eb3767c0747eed80f6e5
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915810"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>받은 편지함 규칙 예상 대로 작동 하지 않습니다.

다음 설정을 확인 합니다.
  
- 전달 또는 자동으로 규칙을 기반으로 받은 편지함 한번만 회신 메시지를 리디렉션할 수 있습니다. (받은 편지함 규칙 또는 메일 흐름 규칙, 전송 규칙으로도 알려져) 리디렉션 규칙 메시지에 최대 10 명의 전달 받는 사람에 게를 추가할 수 있습니다. 자세한 내용은 [저널, 전송 및 받은 편지함 규칙 제한](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)을 참조 하십시오.
    
- 받은 편지함 규칙을 대체 저널링 사서함에서 작동 하지 않습니다. 대체 저널링 사서함에 대 한 자세한 내용은 [대체 저널링 사서함](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox)을 참조 하십시오.
    
이러한 문제를 해결 하려면 [KB 2829319](https://support.microsoft.com/kb/2829319)을 참조 하십시오.
  
이전 문제를 적용 하지, Microsoft 기술 지원 서비스에 게 문제를 에스컬레이션하기 전에 받은 편지함 규칙 진단 보고서를 실행 합니다.
  
1. 웹에서 Outlook에서 사서함을 열고 **설정** 을 클릭 \> **옵션** \> **역할별로 전자 메일** \> **받은 편지함 규칙**입니다.
    
2. 페이지의 맨 아래에 **하는 경우 규칙에서 작동 하지 않는 문제 진단 보고서를 생성 하려면 여기를 클릭**합니다.를 클릭 합니다.
    

