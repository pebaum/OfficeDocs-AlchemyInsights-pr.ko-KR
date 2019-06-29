---
title: 오류 코드 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.
ms.openlocfilehash: e2249d8ebbd2313c64dda5656a3243fa76d97a9a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35388251"
---
<span data-ttu-id="2d954-103">RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="2d954-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="2d954-104">**레지스트리 키**</span><span class="sxs-lookup"><span data-stu-id="2d954-104">**Registry key**</span></span>|<span data-ttu-id="2d954-105">**유형**</span><span class="sxs-lookup"><span data-stu-id="2d954-105">**Type**</span></span>|<span data-ttu-id="2d954-106">**값**</span><span class="sxs-lookup"><span data-stu-id="2d954-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="2d954-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="2d954-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="2d954-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="2d954-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="2d954-109">1 </span><span class="sxs-lookup"><span data-stu-id="2d954-109">1</span></span>  <br/> |

<span data-ttu-id="2d954-110">자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2d954-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="2d954-111">ADAL은 Office 365 ProPlus 및 Office 2016에서 기본적으로 사용 하도록 설정 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d954-111">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="2d954-112">이전에 > RDS (원격 데스크톱 서비스)를 터미널 서비스 라고 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d954-112">>  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  