---
title: 정크 메일로 보내는 아웃 바운드 전자 메일 폴더
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 371d2c46e9048365fd343145330536bd9cf1db82
ms.sourcegitcommit: 1002f510fadb92c143cd6bbb60b42a851d5a38e1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/20/2019
ms.locfileid: "37062800"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="5553c-102">정크 메일로 보내는 아웃 바운드 전자 메일 폴더</span><span class="sxs-lookup"><span data-stu-id="5553c-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="5553c-103">정크로 표시 되는 아웃 바운드 메시지를 확인 하는 경우 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="5553c-104">아직 없는 경우에는 [아웃 바운드 스팸 정책 알림을 구성](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy)하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="5553c-105">[메시지 추적](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) 을 사용 하 여 아웃 바운드 메시지에 추가 세부 정보가 포함 된 이벤트 값 **스팸** 이 있는지 확인 합니다 ( **높은 위험 배달 풀 사용**).</span><span class="sxs-lookup"><span data-stu-id="5553c-105">Use [message trace](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="5553c-106">이러한 메시지에 대해 메시지 콘텐츠를 확인 하 여 스팸으로 간주 되는 것을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="5553c-107">예를 들어 서명이 있으면 대부분의 사용자에 게 문제가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="5553c-108">정크로 표시 되는 합법적인 아웃 바운드 메시지의 예가 여러 개 있는 경우 지원 티켓을 열고 지원 담당자에 게 스팸 분석가에 게 메시지를 가양성으로 전송 해 달라고 요청 합니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="5553c-109">모든 메시지 헤더를 포함 하는 예제 메시지를 제공할 준비를 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="5553c-109">Be prepared to provide sample messages that include all message headers.</span></span>
