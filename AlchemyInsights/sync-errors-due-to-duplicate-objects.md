---
title: 902 (중복 된 개체로 인 한 동기화 오류)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: eac74a6d4de58c9cdbdc8e8df8f705293bb12e87
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30781267"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="ba208-102">개체가 중복 되어 동기화 오류가 발생 했습니다.</span><span class="sxs-lookup"><span data-stu-id="ba208-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="ba208-103">디렉터리 동기화가 완료 되 면 다음 오류 메시지 중 하나가 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ba208-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="ba208-104">이 개체와 연결 된 다음 특성은 로컬 디렉터리의 다른 개체와 이미 연결 되어 있을 수 있는 값을 가지 므로 Microsoft Online Services에서이 개체를 업데이트할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ba208-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="ba208-105">프록시 주소가 같은 synchronized 개체가 Microsoft Online Services 디렉터리에 이미 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ba208-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="ba208-106">이 개체와 연결 된 다음 특성에 로컬 디렉터리 서비스의 다른 개체와 이미 연결 되어 있을 수 있는 값이 있기 때문에이 개체를 업데이트할 수 없습니다. UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="ba208-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="ba208-107">이 문제를 확인 하 고 해결 하려면 [idfix DirSync 오류 수정 도구](https://www.microsoft.com/download/details.aspx?id=36832)를 다운로드 하 여 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="ba208-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="ba208-108">자세한 내용은 [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="ba208-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  

