---
title: 외부 사용자와 공유가 작동 하지 않습니다.
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 20b538846997c021b6e88596a1e8aff401ea935b
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29900881"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>외부 사용자와 SharePoint 콘텐츠를 공유 하는 문제를 해결 합니다.

외부 공유 켜져 조직에 있는지 확인 합니다.
  
1. 이동 하는 [서비스 &amp; Office 365 관리 센터에서 추가 기능 페이지](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), **사이트**를 클릭 하 고 있습니다.
    
2. "On"으로 설정 되어 있는지 확인 "기존 외부 사용자만" 선택 하는 경우 외부 사용자는 Office 365 관리 센터에 나열 되어있는지 확인 합니다.
    
전화번호를 공유 하는 외부 사이트에 대 한 켜져 있는지 확인 하십시오. 클래식 사이트 모음:
  
1. 클래식 SharePoint 관리 센터의 왼쪽된 창에서 **사이트 모음**을 클릭 합니다.
    
2. 사이트 또는 사이트를 선택 하 고 리본 메뉴에서 **공유**를 클릭 합니다.
    
Office 365 그룹에 속해 있는 팀 사이트 또는 통신 사이트:
  
- 이러한 새 사이트 유형 조직 전체의 설정을 로그인 필요 하지 않은 링크를 사용 하 여 파일 공유를 허용 하지 않는 한는 동일한 공유를 설정 하면 조직 전체의 설정으로 포함 합니다. 이 경우 사이트에 로그인 하는 기존 및 새 외부 사용자와 공유를 허용 합니다. 특정 사이트에 대 한 설정을 변경 하려면 새 SharePoint 관리 센터 (미리 보기) 또는 PowerShell을 사용 합니다. [자세한 내용](https://go.microsoft.com/fwlink/?linkid=871863)입니다.
    
> [!NOTE]
> 모든 사이트에 대 한 외부 공유 설정을 조직 차원의 설정 보다 더 하지 허용 하지만 조직 차원의 설정에 권한 보다 제한적인 하나일 수 있습니다. 
  

