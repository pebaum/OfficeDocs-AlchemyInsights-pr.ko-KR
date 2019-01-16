---
title: 1554 Winsock 오류 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 96a9cfd11941158ddf13655c74974e3eb800e570
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298762"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="ed42a-102">Winsock 오류 10061</span><span class="sxs-lookup"><span data-stu-id="ed42a-102">Winsock error 10061</span></span>

<span data-ttu-id="ed42a-p101">이 오류 코드는 Office 365와 대상 호스트 TCP 소켓 (연결)을 설정할 수 없으며 의미 합니다. 이 오류의 원인은 방화벽 구성에 문제가 있는 경우 이 문제를 해결 하려면 이러한 설정을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="ed42a-p101">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host. The most likely cause of this error is a problem with your firewall configuration. To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="ed42a-106">[Office 365 Url 및 IP 주소 범위의](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) 정보를 사용 하 여 방화벽 구성 확인</span><span class="sxs-lookup"><span data-stu-id="ed42a-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="ed42a-107">오류를 Exchange Online Protection (EOP) 특정 있으면 있습니다 해야 이전에 알렸습니다를 [Exchange Online Protection IP 주소](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)에 대 한 변경 합니다.</span><span class="sxs-lookup"><span data-stu-id="ed42a-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="ed42a-108">인터넷 서비스 공급자 (ISP) 포트를 차단 되지 않습니다 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="ed42a-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="ed42a-109">커넥터에서 스마트 호스트 및 대상 서버 설정을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="ed42a-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="ed42a-110">참고 Office 365 이러한 방식으로 *들어오는* 연결을 차단 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ed42a-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  

