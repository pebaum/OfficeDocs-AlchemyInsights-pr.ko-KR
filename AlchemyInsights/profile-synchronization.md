---
title: 프로필 동기화
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29920094"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="d12ca-102">SharePoint 사용자 프로필 응용 프로그램에 변경 된 내 프로필 동기화 수행 때 하 시겠습니까?</span><span class="sxs-lookup"><span data-stu-id="d12ca-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="d12ca-103">SharePoint Online은 사용자 프로필 응용 프로그램으로 사용자 및 그룹을 가져오려면 Active Directory 가져오기 타이머 작업 (AD 가져오기)를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="d12ca-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="d12ca-p101">AD 가져오기 동기화 SharePoint Online 디렉터리 저장소에서 사용자 프로필 응용 프로그램으로 변경 합니다. 이러한 변경 내용은 일괄 처리에서 처리 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d12ca-p101">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application. These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="d12ca-106">변경 내용이 동기화 될 때까지 타이머 작업을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d12ca-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="d12ca-p102">작업 실행을 걸리는 시간 처리에 대 한 변경 수에 따라 달라 집니다. 변경 된 많은 시간이 오래 걸립니다. 서비스 수준 계약 (SLA) SharePoint 온라인 디렉터리에서 사용자에 대 한 변경 24 시간 내에 사용자 프로필 응용 프로그램에 반영할는 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d12ca-p102">The time it takes the job to run depends on the number of changes to process. A large number of changes takes longer. The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="d12ca-110">SharePoint Online에서 사용자 프로필 동기화에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="d12ca-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

