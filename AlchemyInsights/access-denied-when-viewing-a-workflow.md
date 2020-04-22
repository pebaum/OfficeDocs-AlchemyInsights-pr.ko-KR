---
title: 워크플로를 볼 때 액세스 거부 됨
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687336"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="046d0-102">워크플로를 볼 때 액세스 거부 됨</span><span class="sxs-lookup"><span data-stu-id="046d0-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="046d0-103">Sharepoint 2013 sharepoint 그룹의 구성원 자격이 모든 사람으로 설정 되어 있지 않으면 SharePoint 그룹에 전자 메일을 보내려고 할 때 "액세스 거부" 라는 오류 메시지가 나타나지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="046d0-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="046d0-104">**이 문제를 해결 하려면 다음 단계를 수행 합니다.**</span><span class="sxs-lookup"><span data-stu-id="046d0-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="046d0-105">모든 사람이 SharePoint 그룹의 구성원을 볼 수 있도록 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="046d0-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="046d0-106">전자 메일의 받는 사람 또는 참조 줄에서 SharePoint 그룹을 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="046d0-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="046d0-107">SharePoint 그룹에 대 한 멤버 자격 표시 유형을 변경할 수 없는 경우 To 또는 CC 줄에 사용자를 명시적으로 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="046d0-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="046d0-108">자세한 내용을 보려면 [HTTP가 허용 되지 않음/_vti_bin/client.svc/sp.utilities.utility.sendemail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="046d0-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  