---
title: 검사 문제해결 사기 검색에 대 한 안전 팁
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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29936366"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="ee286-102">검사 문제해결 사기 검색에 대 한 안전 팁</span><span class="sxs-lookup"><span data-stu-id="ee286-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="ee286-p101">하는 경우 "보낸 사용해 사기 감지 검사 실패 하 고 있는 것으로 표시 되지 않을 수 있습니다", 이라는 안전 팁을 시작 하 고 보낸 DKIM 또는 SPF 인증 검사를 통과 하지 못했습니다. 이 해결 하는 최상의 방법 보낸 사람이 직접 대 한 권한 부여를입니다. 보낸 사람이 사용자를 대신 하 여를 보내는 경우 SPF 레코드를 보낸 사람의 IP 주소를 추가 하 여 해당 권한을 부여 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ee286-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="ee286-106">추가 정보에 대 한 [검사 빨간색 (의심 스러운) 안전 팁 사기 검색에 대 한 문제를 해결](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="ee286-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="ee286-107">도움이 되는 다른 일부 링크는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="ee286-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="ee286-108">Office 365 스푸핑 방지 하기 위해 보낸 사람이 정책 프레임 워크 (SPF)을 사용 하는 방법</span><span class="sxs-lookup"><span data-stu-id="ee286-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="ee286-109">스푸핑을 방지할 수 있도록 Office 365에서 SPF 설정</span><span class="sxs-lookup"><span data-stu-id="ee286-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

