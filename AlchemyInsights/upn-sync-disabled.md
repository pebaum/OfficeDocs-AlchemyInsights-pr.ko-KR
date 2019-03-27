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
ms.openlocfilehash: 2a03ac64d92c07b523b015850251b33c58bb76f8
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30767241"
---
# <a name="upn-sync-disabled"></a>UPN 동기화 사용 안 함

2016 년 3 월 30 일 이전에 azure ad에 동기화를 시작한 경우 다음 azure ad PowerShell cmdlet을 실행 하 여 조직에 대해서만 UPN 소프트 일치를 사용 하도록 설정 합니다.
  
 **MsolDirSyncFeature-EnableSoftMatchOnUpn 기능을 사용 하도록 설정 $True**
  
UPN soft match는 Azure AD에 대 한 동기화를 시작한 조직에 대해 자동으로 설정 되며, 2016 년 3 월 30 일 이후에 시작 됩니다.
  
UPN 및 기타 동기화 기능에 대해 소프트 일치를 사용 하도록 설정 하는 방법에 대 한 자세한 내용은 [Azure AD Connect sync service 기능](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)을 참조 하세요.
  

