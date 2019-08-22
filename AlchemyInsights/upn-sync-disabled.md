---
title: UPN 동기화 사용 안 함
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: f390d659b191fa4c44bd7c8acb32409cd3021489
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36532337"
---
# <a name="upn-sync-disabled"></a>UPN 동기화 사용 안 함

2016 년 3 월 30 일 이전에 Azure AD에 동기화를 시작한 경우 다음 Azure AD PowerShell cmdlet을 실행 하 여 조직에 대해서만 UPN 소프트 일치를 사용 하도록 설정 합니다.
  
 **MsolDirSyncFeature-EnableSoftMatchOnUpn 기능을 사용 하도록 설정 $True**
  
UPN soft match는 Azure AD에 대 한 동기화를 시작한 조직에 대해 자동으로 설정 되며, 2016 년 3 월 30 일 이후에 시작 됩니다.
  
UPN 및 기타 동기화 기능에 대해 소프트 일치를 사용 하도록 설정 하는 방법에 대 한 자세한 내용은 [AZURE AD Connect sync service 기능](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)을 참조 하세요.
  

