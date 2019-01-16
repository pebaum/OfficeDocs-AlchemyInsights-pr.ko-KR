---
title: 1065 사용 하지 않는의 EOP 아웃 바운드 IP 주소 rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: ec87141ffaa2fa3484620a9b52851e3e92f20b6b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298904"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="4ce39-102">사용 하지 않는 EOP 아웃 바운드 IP 주소 범위</span><span class="sxs-lookup"><span data-stu-id="4ce39-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="4ce39-p101">(2018 년 10 월 26, 의해 수정 되지) 하는 경우 온-프레미스 또는 외부 대상에 메일 흐름을 중단 될 수 있습니다는 사용자의 조직과 잠재적인 문제를 발견 했을 때 했습니다. IP 주소 범위 관리를 단순화 하기 위해 이전에 결정으로 Office 365의 외부 전자 메일 송수신에 사용 되는 Exchange Online Protection (EOP) IP 주소 범위 통합 하는 합니다. 이 분석 하나 이상의 외부 전자 메일 원본 또는 대상 메일 흐름 커넥터에 구성 했을 때의 IP 주소 범위에 표시 된 [여기](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)에서 연결을 수락 되지 않은 나타냅니다.</span><span class="sxs-lookup"><span data-stu-id="4ce39-p101">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations. As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365. Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="4ce39-106">이러한 원본 및 대상 [EOP IP 주소를 게시](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)하는 모든 간에 연결을 허용할 수 있도록 년 10 월 26 전에 역할을 합니다.</span><span class="sxs-lookup"><span data-stu-id="4ce39-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="4ce39-107">이 변경 하는 방법에 대 한 자세한 내용은 메시지 센터 게시물 [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)또는 [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274)참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4ce39-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>
  
 <span data-ttu-id="4ce39-p102">**참고**: 이전에 HTML, XML, and RSS를 통해 IP 또는 URL 게시를 사용 하는 끝점 업데이트에 대 한 경우도 마이그레이션해야 이러한 종류의 업데이트 자동화 (영문)에 대 한 새 웹 서비스에 있습니다. 자세한 내용은 [Office 365 끝점 범주 및 Office 365 IP 주소 및 웹 서비스 URL](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638)참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4ce39-p102">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates. For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
  

