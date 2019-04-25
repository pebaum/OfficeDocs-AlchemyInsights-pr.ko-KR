---
title: 외부 그룹을 사용 하지 않도록 설정 하는 방법
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4d911c319c3e8e327f9b3af3ba67816e646bc468
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32399669"
---
# <a name="how-to-disable-external-groups"></a>외부 그룹을 사용 하지 않도록 설정 하는 방법

Yammer 외부 메시징은 회사 정보가 공유 되지 않도록 하는 자동 관리 제어 집합인 etrs (Exchange 전송 규칙)를 적용 합니다. 사용자가 외부 그룹을 만들지 못하도록 제한 하려면 exchange 전송 규칙 (etr)을 구성한 다음 exchange 전송 규칙을 사용 하 여 외부 메시지를 차단 하도록 Yammer를 구성 해야 합니다. 
  
Exchange Online 관리 센터에서 규칙을 만들었으면 다음 단계에 따라 Yammer에서 etr을 적용 하도록 설정 합니다.
  
- 확인 된 관리자로 yammer에 로그온 하 고 **yammer 관리 센터**에서 C ** \> ontent 및 보안 보안 설정으로 이동 합니다.**
    
- **외부 메시징**에서 **Yammer에서 exchange Online exchange 전송 규칙 (etrs) 적용을 선택 합니다.**
    
- **저장**을 선택합니다. 
    
자세한 내용은 [Exchange 전송 규칙을 사용 하 여 Yammer 네트워크에서 외부 메시징 제어](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9) 를 참조 하세요.
  

