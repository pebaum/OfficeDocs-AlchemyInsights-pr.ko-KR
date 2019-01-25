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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499388"
---
<span data-ttu-id="50b34-103">원격 데스크톱 서비스 (RDS) 배포에서 Office 2013을 활성화 하는 동안 오류가 수신 중인 경우, 하는 경우에 레지스트리를 편집 하 여 ADAL를 사용 하도록 설정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="50b34-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="50b34-104">**레지스트리 키**</span><span class="sxs-lookup"><span data-stu-id="50b34-104">**Registry key**</span></span>|<span data-ttu-id="50b34-105">**유형**</span><span class="sxs-lookup"><span data-stu-id="50b34-105">**Type**</span></span>|<span data-ttu-id="50b34-106">**값**</span><span class="sxs-lookup"><span data-stu-id="50b34-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="50b34-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="50b34-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="50b34-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="50b34-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="50b34-109">^1</span><span class="sxs-lookup"><span data-stu-id="50b34-109">1</span></span>  <br/> |
   
<span data-ttu-id="50b34-110">자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="50b34-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="50b34-p101">ADAL은 Office 365 ProPlus 및 Office 2016에서 기본적으로 활성화 됩니다. 원격 데스크톱 서비스 (RDS) gt_ 터미널 서비스 이름이 이전에 였습니다.</span><span class="sxs-lookup"><span data-stu-id="50b34-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

