---
title: 사기 감지 확인을 위한 보안 팁 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 98627edcd2b685673dda8a8a18821eddf9b64bc1
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32391215"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="08ec4-102">사기 감지 확인을 위한 보안 팁 문제 해결</span><span class="sxs-lookup"><span data-stu-id="08ec4-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="08ec4-103">"보낸 사람이 사기 감지 확인에 실패 하 여 표시 되는 사용자가 아닌 경우" 라는 안전 팁이 나타나면 보낸 사람이 dkim 또는 SPF 인증 검사를 통과 하지 못한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="08ec4-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="08ec4-104">이 문제를 해결 하는 가장 좋은 방법은 보낸 사람이 자신에 게 권한을 부여 하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="08ec4-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="08ec4-105">보낸 사람이 사용자를 대신 하 여 보내는 경우에는 SPF 레코드에 보낸 사람의 IP 주소를 추가 하 여 권한을 부여 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="08ec4-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="08ec4-106">자세한 내용은 [사기 검색 검사에 대 한 위험 (의심 스러운) 보안 팁 문제 해결](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) 을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="08ec4-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="08ec4-107">다음은 도움이 될 수 있는 몇 가지 링크입니다.</span><span class="sxs-lookup"><span data-stu-id="08ec4-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="08ec4-108">Office 365에서 SPF (sender policy framework)를 사용 하 여 스푸핑을 방지 하는 방법</span><span class="sxs-lookup"><span data-stu-id="08ec4-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="08ec4-109">스푸핑을 방지할 수 있도록 Office 365에서 SPF 설정</span><span class="sxs-lookup"><span data-stu-id="08ec4-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

