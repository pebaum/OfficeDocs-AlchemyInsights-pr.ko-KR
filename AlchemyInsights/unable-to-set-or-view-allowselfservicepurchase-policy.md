---
title: AllowSelfServicePurchase 정책을 설정 하거나 볼 수 없습니다.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: 587a05cccbc71a970d4bd7723bff0df0c3b64ccc
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158567"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a><span data-ttu-id="e80b7-102">AllowSelfServicePurchase 정책을 설정 하거나 볼 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-102">Unable to set or view the AllowSelfServicePurchase policy</span></span>

<span data-ttu-id="e80b7-103">AllowSelfServicePurchase 정책을 설정 하거나 확인 하려고 하면 다음과 같은 오류 메시지가 나타납니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-103">When attempting to set or view the AllowSelfServicePurchase policy, you receive the following error message:</span></span>

<span data-ttu-id="e80b7-104">*HandleError: PolicyId가 ' AllowSelfServicePurchase ' 인 제품 정책을 검색 하지 못했습니다. ErrorMessage-기본 연결이 닫혔습니다. 보내기에서 예기치 않은 오류가 발생 했습니다.*</span><span class="sxs-lookup"><span data-stu-id="e80b7-104">*HandleError : Failed to retrieve product policy with PolicyId 'AllowSelfServicePurchase', ErrorMessage - The underlying connection was closed: An unexpected error occurred on a send.*</span></span>

<span data-ttu-id="e80b7-105">이전 버전의 TLS (전송 계층 보안)로 인 한 것일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-105">This may be due to an older version of Transport Layer Security (TLS).</span></span> <span data-ttu-id="e80b7-106">MSCommerce 서비스에 연결 하려면 TLS 1.2 이상을 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-106">To connect the MSCommerce service, you need to use TLS 1.2 or greater.</span></span>  

<span data-ttu-id="e80b7-107">다음 단계를 수행 하 여 TLS 프로토콜을 1.2으로 설정 하 고 확인 하 고 다시 시도 합니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-107">Try the following steps to enable/set the TLS protocol to 1.2, verify, and retry.</span></span>
 1. <span data-ttu-id="e80b7-108">PowerShell 명령 프롬프트 (PS C:\) 다음 명령을 입력 하 여 TLS 프로토콜을 버전 1.2으로 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-108">At the PowerShell command prompt (PS C:\) enter the following command to set the TLS protocol to version 1.2:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12`

2. <span data-ttu-id="e80b7-109">다음 명령을 사용 하 여 사용 중인 TLS 프로토콜을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-109">Verify the TLS protocol(s) in use, with the following command:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol` 

3. <span data-ttu-id="e80b7-110">필요에 따라 가져오기 또는 업데이트 명령을 다시 시도 합니다.</span><span class="sxs-lookup"><span data-stu-id="e80b7-110">Retry the Get or Update commands as needed.</span></span>

