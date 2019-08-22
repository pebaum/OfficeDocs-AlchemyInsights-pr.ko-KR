---
title: "\"누락 된 파일 또는 폴더 문제 해결"
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 1fab9c5d-f6ca-461c-94f0-76e7cfb8a26d
ms.openlocfilehash: 0105c6e6fa6e44371dc260edc438ebfaf6919bda
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36559919"
---
# <a name="troubleshooting-missing-files-or-folders-in-onedrive-or-sharepoint"></a><span data-ttu-id="34491-102">OneDrive 또는 SharePoint에서 누락 된 파일 또는 폴더 문제 해결</span><span class="sxs-lookup"><span data-stu-id="34491-102">Troubleshooting missing Files or Folders in OneDrive or SharePoint</span></span>

- [<span data-ttu-id="34491-103">사이트의 휴지통 확인</span><span class="sxs-lookup"><span data-stu-id="34491-103">Check the recycle bin of the site</span></span>](https://support.office.com/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US)

- [<span data-ttu-id="34491-104">SharePoint 사이트의 휴지통에서 항목 복원</span><span class="sxs-lookup"><span data-stu-id="34491-104">Restore items in the Recycle Bin of a SharePoint site</span></span>](https://support.office.com/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)



<span data-ttu-id="34491-105">**파일 복원 기능**</span><span class="sxs-lookup"><span data-stu-id="34491-105">**Files Restore feature**</span></span>

<span data-ttu-id="34491-106">OneDrive 또는 SharePoint 파일의 수가 너무 많이 삭제, 덮어쓰기, 손상 또는 감염 된 경우 파일 복원 기능을 사용 하 여 전체 OneDrive 또는 Sharepoint 라이브러리를 이전 시간으로 복원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="34491-106">If lots of your OneDrive or SharePoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or Sharepoint library to a previous time using the files restore feature.</span></span>

- [<span data-ttu-id="34491-107">OneDrive 라이브러리 복원</span><span class="sxs-lookup"><span data-stu-id="34491-107">Restore a OneDrive library</span></span>](https://support.office.com/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

- [<span data-ttu-id="34491-108">문서 라이브러리 복원</span><span class="sxs-lookup"><span data-stu-id="34491-108">Restore a Document library</span></span>](https://support.office.com/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a?ui=en-US&amp;rs=en-US&amp;ad=US)

<span data-ttu-id="34491-109">**감사 로깅 또는 파일 활동 창을 사용 하 여 파일 기록을 확인 합니다.**</span><span class="sxs-lookup"><span data-stu-id="34491-109">**Use audit logging or the file activity pane to check history of the file**</span></span>

<span data-ttu-id="34491-110">[](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fen-us%252farticle%252fsearch-the-audit-log-in-the-office-365-protection-center-0d4d0f35-390b-4518-800e-0c7ec95e946c)</a> [여기](https://protection.office.com/#/unifiedauditlog) 로 탐색 하 여 감사 보고서 확인</span><span class="sxs-lookup"><span data-stu-id="34491-110">[Check the audit reports](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fen-us%252farticle%252fsearch-the-audit-log-in-the-office-365-protection-center-0d4d0f35-390b-4518-800e-0c7ec95e946c)</a> by navigating [here](https://protection.office.com/#/unifiedauditlog)</span></span>

<span data-ttu-id="34491-111">파일 [활동](https://support.office.com/article/File-activity-in-a-document-library-6105ecda-1dd0-4f6f-9542-102bf5c0ffe0) 창을 사용 하 여 파일의 기록을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="34491-111">Use the [file activity](https://support.office.com/article/File-activity-in-a-document-library-6105ecda-1dd0-4f6f-9542-102bf5c0ffe0) pane to check the history of the file.</span></span>

<span data-ttu-id="34491-112">로컬 컴퓨터에서 OneDrive 동기화 클라이언트를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="34491-112">Check the OneDrive Sync Client on your local machine.</span></span>  <span data-ttu-id="34491-113">OneDrive 동기화 클라이언트를 통해 컴퓨터의 파일을 동기화 하는 경우 로컬 동기화 폴더가 올바르게 업로드 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="34491-113">If you're syncing the files on your computer via OneDrive Sync client, check the local sync folder to ensure that it has been properly uploaded.</span></span> <span data-ttu-id="34491-114">로컬 컴퓨터에서 휴지통이 있는지도 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="34491-114">Ensure you also check the recycle bin on your local machine.</span></span>



