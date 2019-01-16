---
title: 워크플로 볼 때 액세스 거부 되었습니다.
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: cced887b03876eef527e0166a5a3c9be4b553029
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298701"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="c543f-102">워크플로 볼 때 액세스 거부 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="c543f-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="c543f-103">SharePoint 2013 워크플로 SharePoint 그룹에 전자 메일을 보내려고 시도 하는 모든 사용자에 게 SharePoint 그룹의 구성원 자격 설정 되지 않은 경우 "액세스 거부" 라는 오류 메시지가 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c543f-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="c543f-104">**이 문제를 해결 하려면 다음이 단계를 수행 합니다.**</span><span class="sxs-lookup"><span data-stu-id="c543f-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="c543f-105">SharePoint 그룹의 구성원을 보려면 모든 사용자에 게 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="c543f-105">Allow everybody to see the members of the SharePoint group.</span></span> 
  
 2. <span data-ttu-id="c543f-106">받는 사람 또는 참조에서 SharePoint 그룹을 제거는 전자 메일의 줄 합니다.</span><span class="sxs-lookup"><span data-stu-id="c543f-106">Remove the SharePoint group from the To or CC line of the email.</span></span> 
  
 3. <span data-ttu-id="c543f-107">받는 사람 또는 참조에는 사용자를 명시적으로 추가 SharePoint 그룹에 대 한 멤버 자격 표시 여부를 변경할 수 없는 경우 선입니다.</span><span class="sxs-lookup"><span data-stu-id="c543f-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span> 
  
<span data-ttu-id="c543f-108">보려면 자세한 내용은 [/_vti_bin/client.svc/sp.utilities.utility.SendEmail에 무단으로 HTTP를 ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409)참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c543f-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  

