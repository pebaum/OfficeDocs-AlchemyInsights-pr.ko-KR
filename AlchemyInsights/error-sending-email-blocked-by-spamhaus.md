---
title: SpamHaus에 의해 차단 되는 전자 메일을 발송 하는 오류
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 249f16d057b0539d71dc514ac35df28ab78fa061
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29912354"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="9ce71-102">전자 메일을 발송 하는 오류: Spamhaus를 사용 하 여 차단 된 클라이언트 호스트</span><span class="sxs-lookup"><span data-stu-id="9ce71-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="9ce71-p101">메시지를 보낸 IP 주소 [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245)소유 하 고 차단 목록에 있는 경우 손상 된 계정을 포함 하는 Spamhaus에 의해 차단 되는 이유는 공용 IP 주소 및 인터넷 서비스 공급자 (ISP) 정책 공유 하는 컴퓨터를 손상 합니다. 문제를 해결할 수는 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ce71-p101">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies. Possible fixes are:</span></span>
  
- <span data-ttu-id="9ce71-106">원본 전자 메일 서버를 제어 하는 경우 Office 365로 차단 된 인바운드 메시지에 대 한 원인을 확인 하 고 Spamhaus 웹사이트에서 블록을 제거 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9ce71-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>
    
- <span data-ttu-id="9ce71-p102">다른 사람에 원본 IP 주소 속한 되 면 Office 365로 차단 된 인바운드 메시지에 대 한 주소 소유자 Spamhaus 웹사이트에서 블록을 제거 해야 합니다. IP 주소가 정책 차단 목록 (PBL) 인 경우 소유자 다른 정적 IP 주소를 할당 하거나 주소는 PBL에서 제거 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ce71-p102">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website. If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>
    
- <span data-ttu-id="9ce71-p103">Office 365 도메인에서 차단 된 아웃 바운드 메시지에 대 한 메시지는 타사 서비스를 통해 라우팅되는 경우이 오류를 받을 수 있습니다. 차단 된 IP 주소 소유자를 찾는 WHOIS 조회 도구를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ce71-p103">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service. You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
    

