---
title: 주소 목록에서 그룹을 숨기 거 나 숨기기 취소 하기 위한 지침
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 61ba34e6d554831da712a92401f26fabb02c26b7
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908350"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a><span data-ttu-id="479ae-102">주소 목록 (GAL)에서 Microsoft 365 그룹 숨기기</span><span class="sxs-lookup"><span data-stu-id="479ae-102">Hide Microsoft 365 group from address list (GAL)</span></span>

<span data-ttu-id="479ae-103">Outlook 또는 OWA와 같은 Exchange 클라이언트의 주소 목록 (GAL)에서 Microsoft 365 그룹을 숨기려면 EXO shell에서 다음 명령을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="479ae-103">To hide an Microsoft 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="479ae-104">Microsoft 365 그룹을 Exchange 클라이언트에 표시 하지 않도록 숨기려면 EXO shell에서 다음 명령을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="479ae-104">To hide the Microsoft 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

