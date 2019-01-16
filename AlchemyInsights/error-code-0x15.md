---
title: 오류 코드 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: 원격 데스크톱 서비스 (RDS) 배포에서 Office 2013을 활성화 하는 동안 오류가 수신 중인 경우, 하는 경우에 레지스트리를 편집 하 여 ADAL를 사용 하도록 설정 하는 것이 좋습니다.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299063"
---
<span data-ttu-id="1c4eb-103">원격 데스크톱 서비스 (RDS) 배포에서 Office 2013을 활성화 하는 동안 오류가 수신 중인 경우, 하는 경우에 레지스트리를 편집 하 여 ADAL를 사용 하도록 설정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="1c4eb-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="1c4eb-104">**레지스트리 키**</span><span class="sxs-lookup"><span data-stu-id="1c4eb-104">**Registry key**</span></span>|<span data-ttu-id="1c4eb-105">**유형**</span><span class="sxs-lookup"><span data-stu-id="1c4eb-105">**Type**</span></span>|<span data-ttu-id="1c4eb-106">**값**</span><span class="sxs-lookup"><span data-stu-id="1c4eb-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="1c4eb-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="1c4eb-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="1c4eb-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="1c4eb-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="1c4eb-109">1</span><span class="sxs-lookup"><span data-stu-id="1c4eb-109">1</span></span>  <br/> |
   
<span data-ttu-id="1c4eb-110">자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="1c4eb-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="1c4eb-p101">ADAL은 Office 365 ProPlus 및 Office 2016에서 기본적으로 활성화 됩니다. > 원격 데스크톱 서비스 (RDS) 터미널 서비스 이름이 이전에 였습니다.</span><span class="sxs-lookup"><span data-stu-id="1c4eb-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

