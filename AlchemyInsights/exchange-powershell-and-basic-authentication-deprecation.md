---
title: Exchange PowerShell과 기본 인증 중단
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "4577"
ms.openlocfilehash: 24d59860732b42e8d62da8c1a8c37f2018a0d126
ms.sourcegitcommit: 264b782ac2fba8ffd84524180dc4f7d60b45e9a4
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/04/2020
ms.locfileid: "44015695"
---
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a><span data-ttu-id="70b15-102">Exchange PowerShell과 기본 인증 중단</span><span class="sxs-lookup"><span data-stu-id="70b15-102">Exchange PowerShell and basic authentication deprecation</span></span>

<span data-ttu-id="70b15-103">기본 인증을 사용하지 않고 Exchange Online PowerShell에 연결하는 방법에 대한 최신 정보는 [여기를 참조하세요](https://aka.ms/psbasicauth).</span><span class="sxs-lookup"><span data-stu-id="70b15-103">For the latest information about how to connect to Exchange Online PowerShell without the use of Basic Authentication, [please go here](https://aka.ms/psbasicauth).</span></span>

<span data-ttu-id="70b15-104">클라이언트 컴퓨터에서 기본 인증은 계속 사용하도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-104">Please note that Basic Authentication still needs to be enabled on your client machine.</span></span>
<span data-ttu-id="70b15-105">새 PowerShell V2 모듈은 최신 인증을 사용하여 모든 REST 기반 V2 Cmdlet을 사용할 수 있도록 연결을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-105">The new PowerShell V2 module uses Modern Auth to establish connection for enabling all of REST-based V2 Cmdlets.</span></span> <span data-ttu-id="70b15-106">V2 cmdlet 외에도 원격 PowerShell 세션을 설정해야 하는 이전의 RPS(원격 PowerShell) Cmdlet에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-106">In addition to V2 cmdlets, it also allows you to access older Remote PowerShell (RPS) Cmdlets which requires a Remote PowerShell session to be established.</span></span> <span data-ttu-id="70b15-107">Windows 컴퓨터에서 RPS 세션을 설정하려면 모듈이 최신 인증 메커니즘을 사용하여 서비스에서 인증을 받는 경우에도, 클라이언트 컴퓨터에서 WinRM BasicAuth를 사용하도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-107">Establishing an RPS session on Windows machine requires WinRM BasicAuth to be enabled on the client machine even though the module uses Modern Auth mechanism to authenticate to the service.</span></span> <span data-ttu-id="70b15-108">WinRM 기본 인증 파이프라인은 최신 인증 토큰을 전송하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-108">The WinRM Basic Auth pipeline is used for transporting Modern Auth tokens.</span></span> <span data-ttu-id="70b15-109">클라이언트 컴퓨터에서 WinRM 기본 인증을 사용하지 않도록 설정한 경우에는 새 V2 cmdlet이 계속 작동하지만 이전 RPS cmdlet은 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="70b15-109">If WinRM Basic Auth is disabled on the client machine, the new V2 cmdlets will continue to work (but the older RPS cmdlets will not).</span></span>
