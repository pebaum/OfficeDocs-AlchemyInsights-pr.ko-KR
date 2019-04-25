---
title: deflectTransport 규칙에 대 한 929 받은 편지함 규칙
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/15/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 929
ms.assetid: 9733ef4e-db8d-4345-a072-c251480875a1
ms.openlocfilehash: 880f4cb2c42a564362ad7832ebf8ced16fd26d77
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32413657"
---
# <a name="mail-flow-rules-also-known-as-transport-rules"></a><span data-ttu-id="860d9-102">메일 흐름 규칙 (전송 규칙이 라고도 함)</span><span class="sxs-lookup"><span data-stu-id="860d9-102">Mail flow rules (also known as transport rules)</span></span>

- <span data-ttu-id="860d9-103">메일 흐름 규칙에 대 한 일반적인 개요: [Exchange Online의 메일 흐름 규칙 (전송 규칙)](https://technet.microsoft.com/library/jj919238.aspx)</span><span class="sxs-lookup"><span data-stu-id="860d9-103">General overview of mail flow rules: [Mail flow rules (transport rules) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span></span>

- <span data-ttu-id="860d9-104">메일 흐름 규칙 설정: [Exchange Online의 메일 흐름 규칙 절차](https://technet.microsoft.com/library/dn600436.aspx)</span><span class="sxs-lookup"><span data-stu-id="860d9-104">Setup mail flow rules: [Mail flow rule procedures in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span></span>

- <span data-ttu-id="860d9-105">메일 흐름 규칙 만들기, 수정 및 삭제: [메일 흐름 규칙 관리](https://technet.microsoft.com/library/jj657505.aspx)</span><span class="sxs-lookup"><span data-stu-id="860d9-105">Create, modify, and delete mail flow rules: [Manage mail flow rules](https://technet.microsoft.com/library/jj657505.aspx)</span></span>

<span data-ttu-id="860d9-106">Exchange Online PowerShell에서 메일 흐름 규칙을 관리할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="860d9-106">You can also manage mail flow rules in Exchange Online PowerShell.</span></span> <span data-ttu-id="860d9-107">자세한 내용은 [Get-new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (보기), [new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (만들기), [제거-new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (삭제), [설정-new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (기존 수정), [disable-new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (기존 항목 사용 안 함) 및 [Enable-new-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (기존 항목 사용)</span><span class="sxs-lookup"><span data-stu-id="860d9-107">For more information, see [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (view), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (delete), [Set-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (modify existing), [Disable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (disable existing), and [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (enable existing).</span></span>

<span data-ttu-id="860d9-108">추가 메일 흐름 규칙 cmdlet: [get-transportruleaction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (사용 가능한 작업 나열), [get-get-transportrulepredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (사용 가능한 조건 및 예외 목록), [내보내기-export-transportrulecollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (규칙 내보내기) [, export-transportrulecollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (가져오기 규칙)</span><span class="sxs-lookup"><span data-stu-id="860d9-108">Additional mail flow rule cmdlets: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (list available actions), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (list available conditions and exceptions), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (export rules), and [Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (import rules).</span></span>
