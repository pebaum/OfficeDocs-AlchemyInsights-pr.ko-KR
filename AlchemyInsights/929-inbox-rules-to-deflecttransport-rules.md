---
title: DeflectTransport 규칙을 929 받은 편지함 규칙
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/15/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 9733ef4e-db8d-4345-a072-c251480875a1
ms.openlocfilehash: ed4afe938b310f1569061ad00bf90ad87e91b465
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299262"
---
# <a name="mail-flow-rules-also-known-as-transport-rules"></a><span data-ttu-id="5a6cd-102">메일 흐름 규칙 (전송 규칙이 라고도 함)</span><span class="sxs-lookup"><span data-stu-id="5a6cd-102">Mail flow rules (also known as transport rules)</span></span>

- <span data-ttu-id="5a6cd-103">메일 흐름 규칙의 일반적인 개요: [메일 흐름 규칙 (전송 규칙) Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span><span class="sxs-lookup"><span data-stu-id="5a6cd-103">General overview of mail flow rules: [Mail flow rules (transport rules) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span></span>
    
- <span data-ttu-id="5a6cd-104">메일 흐름 규칙 설정: [메일 흐름 규칙 절차 Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span><span class="sxs-lookup"><span data-stu-id="5a6cd-104">Setup mail flow rules: [Mail flow rule procedures in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span></span>
    
- <span data-ttu-id="5a6cd-105">만들기, 수정 및 메일 흐름 규칙 삭제: [메일 흐름 규칙 관리](https://technet.microsoft.com/library/jj657505.aspx)</span><span class="sxs-lookup"><span data-stu-id="5a6cd-105">Create, modify, and delete mail flow rules: [Manage mail flow rules](https://technet.microsoft.com/library/jj657505.aspx)</span></span>
    
<span data-ttu-id="5a6cd-p101">또한 Exchange Online PowerShell에서 메일 흐름 규칙을 관리할 수 있습니다. 자세한 내용은 [Get-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (보기) [New-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) 을 참조 하십시오. (만들기) [Remove-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (삭제), [Set-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (기존 항목 수정), [Disable-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (사용 안함 기존) 및 [Enable-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) 설정 (기존).</span><span class="sxs-lookup"><span data-stu-id="5a6cd-p101">You can also manage mail flow rules in Exchange Online PowerShell. For more information, see [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (view), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (delete), [Set-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (modify existing), [Disable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (disable existing), and [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (enable existing).</span></span> 
  
<span data-ttu-id="5a6cd-108">추가 메일 흐름 규칙 cmdlet: [Get-transportruleaction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (사용 가능한 동작 목록), [Get-transportrulepredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (목록 사용할 수 있는 조건 및 예외), [Export-transportrulecollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (내보내기 규칙) 및 [ 가져오기 TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (규칙 가져오기).</span><span class="sxs-lookup"><span data-stu-id="5a6cd-108">Additional mail flow rule cmdlets: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (list available actions), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (list available conditions and exceptions), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (export rules), and [Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (import rules).</span></span> 
  

