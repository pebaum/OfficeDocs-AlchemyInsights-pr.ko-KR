---
title: 1332 OWA-받은 편지함 규칙 실행 중인 아닌 사서함에 대 한
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f090d0a9d84bc6a4d1a1f4c0af55102d4b0ddfbe
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478647"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="cb1da-102">받은 편지함 규칙 예상 대로 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="cb1da-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="cb1da-103">다음 설정을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="cb1da-103">Verify the following settings:</span></span>
  
- <span data-ttu-id="cb1da-p101">전달 또는 자동으로 규칙을 기반으로 받은 편지함 한번만 회신 메시지를 리디렉션할 수 있습니다. (받은 편지함 규칙 또는 메일 흐름 규칙, 전송 규칙으로도 알려져) 리디렉션 규칙 메시지에 최대 10 명의 전달 받는 사람에 게를 추가할 수 있습니다. 자세한 내용은 [저널, 전송 및 받은 편지함 규칙 제한](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="cb1da-p101">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time. A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message. For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>
    
- <span data-ttu-id="cb1da-p102">받은 편지함 규칙을 대체 저널링 사서함에서 작동 하지 않습니다. 대체 저널링 사서함에 대 한 자세한 내용은 [대체 저널링 사서함](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="cb1da-p102">Inbox rules don't work on the alternate journaling mailbox. For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>
    
<span data-ttu-id="cb1da-109">이러한 문제를 해결 하려면 [KB 2829319](https://support.microsoft.com/kb/2829319)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="cb1da-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>
  
<span data-ttu-id="cb1da-110">이전 문제를 적용 하지, Microsoft 기술 지원 서비스에 게 문제를 에스컬레이션하기 전에 받은 편지함 규칙 진단 보고서를 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="cb1da-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>
  
1. <span data-ttu-id="cb1da-111">웹에서 Outlook에서 사서함을 열고 **설정** 을 클릭 \> **옵션** \> **역할별로 전자 메일** \> **받은 편지함 규칙**입니다.</span><span class="sxs-lookup"><span data-stu-id="cb1da-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>
    
2. <span data-ttu-id="cb1da-112">페이지의 맨 아래에 **하는 경우 규칙에서 작동 하지 않는 문제 진단 보고서를 생성 하려면 여기를 클릭**합니다.를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="cb1da-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
    

