---
title: 902 (개체가 중복으로 인해 동기화 오류)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f8db233167a5e2b2ef7290438b8e6d92d0dccb1e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478677"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="b23ae-102">개체가 중복으로 인해 동기화 오류</span><span class="sxs-lookup"><span data-stu-id="b23ae-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="b23ae-103">디렉터리 동기화가 완료 되 면 다음과 같은 오류 메시지 중 하나가 나타날 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b23ae-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="b23ae-104">이 개체와 관련 된 다음과 같은 특성 값 이미 로컬 디렉터리에서 다른 개체와 연결 될 수 있으므로 Microsoft 온라인 서비스에서이 개체를 업데이트할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b23ae-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="b23ae-105">동일한 프록시 주소와 동기화 된 개체는 Microsoft Online Services 디렉터리에 이미 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b23ae-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="b23ae-106">이 개체와 관련 된 다음과 같은 특성 값 이미 로컬 디렉터리 서비스에서 다른 개체와 연결 될 수 있으므로이 개체를 업데이트할 수 없음: UserPrincipalName입니다.</span><span class="sxs-lookup"><span data-stu-id="b23ae-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="b23ae-107">를 확인 하 고 문제를 해결 하려면 다운로드 하 여 [IdFix DirSync 오류 수정 도구](https://www.microsoft.com/download/details.aspx?id=36832)를 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="b23ae-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="b23ae-108">자세한 내용은 [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="b23ae-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  

