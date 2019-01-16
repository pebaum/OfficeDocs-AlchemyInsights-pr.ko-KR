---
title: 설정 또는 공용 폴더 사용 권한 변경
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: d537f1446318f1507f52297e547789fdf246b322
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28298934"
---
# <a name="permissions-and-public-folders"></a><span data-ttu-id="38693-102">사용 권한 및 공용 폴더</span><span class="sxs-lookup"><span data-stu-id="38693-102">Permissions and Public Folders</span></span>

<span data-ttu-id="38693-103">Outlook에서 Exchange 관리 센터 (EAC)를 사용 하 여 공용 폴더에서 사용 권한을 변경할 수 있습니다 또는 PowerShell:</span><span class="sxs-lookup"><span data-stu-id="38693-103">You can change the permissions on your Public Folders using Outlook, the Exchange admin center (EAC), or PowerShell:</span></span>
  
- <span data-ttu-id="38693-104">Outlook 지침은, [여기를 클릭](https://support.office.com/article/https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx)합니다.</span><span class="sxs-lookup"><span data-stu-id="38693-104">For Outlook instructions, [click here](https://support.office.com/article/https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).</span></span>
    
- <span data-ttu-id="38693-p101">EAC를 대 한 자세한 내용이 [은이 문서](https://support.office.com/article/https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) 참조 하십시오. 클릭 수 [여기](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) EAC를 탐색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="38693-p101">For EAC, refer to [this article](https://support.office.com/article/https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) for instructions. You can click [here](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) to navigate to EAC.</span></span> 
    
- <span data-ttu-id="38693-p102">Powershell을 Add-publicfolderclientpermission commandlet을 사용 하 여 대 한 자세한 내용이 [은이 문서](https://support.office.com/article/https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) 참조 합니다. Exchange Powershell에 연결 하는 지침을 보려면 클릭 [여기](https://support.office.com/article/https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx)합니다.</span><span class="sxs-lookup"><span data-stu-id="38693-p102">For Powershell, refer to [this article](https://support.office.com/article/https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) for instructions on using the Add-PublicFolderClientPermission commandlet. If you need instructions to connect to Exchange Powershell, click [here](https://support.office.com/article/https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).</span></span>
    
<span data-ttu-id="38693-p103">외부 전자 메일 배달에 필요한 수 **외부 사용자가 메일 사용이 가능한 공용 폴더에 대 한 전자 메일을 보낼 수 없습니다.**, 이유 하는 경우를 공용 폴더 사용 권한 없음을 수 있습니다. Outlook 지침을 사용 하 여 해결할 수 있습니다 [여기](https://support.office.com/article/https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)또는 PowerShell 명령을 사용 하 여 [여기](https://support.office.com/article/https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx)합니다.</span><span class="sxs-lookup"><span data-stu-id="38693-p103">If **external users can't send emails to a mail-enabled Public Folder**, the reason might be that the public folder is missing permissions required for external email delivery. You can fix this using the Outlook instructions [here](https://support.office.com/article/https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1), or the PowerShell instructions [here](https://support.office.com/article/https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).</span></span>
  

