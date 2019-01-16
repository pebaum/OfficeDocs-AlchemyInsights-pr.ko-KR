---
title: UPN 동기화 사용 안함
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: d00f10688ec775c22d60a9089e291c265ada46f1
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299608"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="5dcb5-102">UPN 동기화 사용 안함</span><span class="sxs-lookup"><span data-stu-id="5dcb5-102">UPN sync disabled</span></span>

<span data-ttu-id="5dcb5-103">2016 년 3 월 30 일 전에 Azure AD를 동기화 하는 중 시작 하는 경우 소프트 일치 하는 조직만에 대 한 UPN을 사용 하도록 설정 하려면 다음 Azure AD PowerShell cmdlet를 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="5dcb5-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="5dcb5-104">**집합 MsolDirSyncFeature-EnableSoftMatchOnUpn 기능-$True를 사용 하도록 설정**</span><span class="sxs-lookup"><span data-stu-id="5dcb5-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="5dcb5-105">자동으로 켜거나 2016 년 3 월 30 일 후 Azure AD를 동기화 하는 중 시작 하는 조직에 대 한 UPN 소프트 일치 켜 집니다.</span><span class="sxs-lookup"><span data-stu-id="5dcb5-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="5dcb5-106">UPN 및 기타 동기화 기능에 대해 부드러운 일치를 사용 하도록 설정 하는 방법에 대 한 자세한 내용은 [Azure AD 연결 동기화 서비스 기능](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="5dcb5-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

