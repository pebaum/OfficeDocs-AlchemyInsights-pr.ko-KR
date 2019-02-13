---
title: UPN 동기화 사용 안함
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 983796ce8fb7e8b52c0ce31aa13597b53cc9e038
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29921714"
---
# <a name="upn-sync-disabled"></a>UPN 동기화 사용 안함

2016 년 3 월 30 일 전에 Azure AD를 동기화 하는 중 시작 하는 경우 소프트 일치 하는 조직만에 대 한 UPN을 사용 하도록 설정 하려면 다음 Azure AD PowerShell cmdlet를 실행 합니다.
  
 **집합 MsolDirSyncFeature-EnableSoftMatchOnUpn 기능-$True를 사용 하도록 설정**
  
자동으로 켜거나 2016 년 3 월 30 일 후 Azure AD를 동기화 하는 중 시작 하는 조직에 대 한 UPN 소프트 일치 켜 집니다.
  
UPN 및 기타 동기화 기능에 대해 부드러운 일치를 사용 하도록 설정 하는 방법에 대 한 자세한 내용은 [Azure AD 연결 동기화 서비스 기능](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)을 참조 하십시오.
  

