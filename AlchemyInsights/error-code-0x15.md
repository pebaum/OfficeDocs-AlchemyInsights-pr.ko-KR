---
title: 오류 코드 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32402745"
---
<span data-ttu-id="b4da6-103">RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="b4da6-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="b4da6-104">**레지스트리 키**</span><span class="sxs-lookup"><span data-stu-id="b4da6-104">**Registry key**</span></span>|<span data-ttu-id="b4da6-105">**유형**</span><span class="sxs-lookup"><span data-stu-id="b4da6-105">**Type**</span></span>|<span data-ttu-id="b4da6-106">**값**</span><span class="sxs-lookup"><span data-stu-id="b4da6-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="b4da6-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="b4da6-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="b4da6-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="b4da6-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="b4da6-109">1 </span><span class="sxs-lookup"><span data-stu-id="b4da6-109">1</span></span>  <br/> |
   
<span data-ttu-id="b4da6-110">자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="b4da6-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="b4da6-111">ADAL은 office 365 ProPlus 및 office 2016에서 기본적으로 사용 하도록 설정 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b4da6-111">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="b4da6-112">이전에는 > RDS (원격 데스크톱 서비스)를 터미널 서비스 라고 합니다.</span><span class="sxs-lookup"><span data-stu-id="b4da6-112">>  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

