---
title: SharePoint 사이트에 그룹 추가
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 6aea12d44a44a3e11eaf3fb1bd47ff3e9dbfd9e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507853"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="0e8b4-102">SharePoint Online에서 연결 된 사이트를 만들거나 그룹화 하는 경우의 문제</span><span class="sxs-lookup"><span data-stu-id="0e8b4-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="0e8b4-103">그룹 연결 사이트를 만들거나 다시 만들 때 몇 가지 일반적인 문제가 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="0e8b4-104">그룹 및 연결 된 사이트를 삭제 하 고 동일한 URL을 사용 하 여 다른 사이트를 만들려는 경우에는 이전 사이트를 영구적으로 제거 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="0e8b4-105">[SPO 관리 셸](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) 다운로드</span><span class="sxs-lookup"><span data-stu-id="0e8b4-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="0e8b4-106">Powershell을 시작 하는 방법에 대 한 자세한 내용은 [SharePoint Online 관리 셸을 시작](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) 하기를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="0e8b4-107">[Remove-spodeletedsite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet을 사용 하 여 삭제 된 사이트에서 사이트를 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="0e8b4-108">그룹 연결 사이트를 만들고 경고를 수신 하는 경우 별칭이 같은 다른 그룹이 이미 있으면 [관리 센터에서 Office 365](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups)의 기존 그룹을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="0e8b4-109">이 문제를 해결 하려면 기존 그룹이 더 이상 필요 하지 않은 경우 삭제 하거나 다른 별칭을 할당 하 여 사이트를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="0e8b4-110">SharePoint에서 최신 그룹을 만들고 사용 하는 방법에는 여러 가지가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="0e8b4-111">기존 사이트를 Office 365 그룹에 연결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="0e8b4-112">자세한 내용은 [Connect a Office 365 group Using SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="0e8b4-113">Office 365 그룹 연결 사이트를 만들려면 팀 사이트를 만들어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="0e8b4-114">자세한 내용은 [SharePoint에서 팀 사이트 만들기](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="0e8b4-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

