---
title: 1336 RecoverableItems 폴더가 꽉 찼습니다.
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 05e7b47a2200c3b0500e7d786166966ea301179a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35370393"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="53aaa-102">복구 가능한 항목 폴더가 꽉 참</span><span class="sxs-lookup"><span data-stu-id="53aaa-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="53aaa-103">Office 365에서 Exchange Online 사서함의 경우 복구 가능한 항목 폴더에 대 한 기본 저장 제한은 30gb입니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-103">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="53aaa-104">사서함이 소송 보존, eDiscovery 365 보류에 있는 경우 복구 가능한 항목 폴더의 저장소 제한은 자동으로 100로 증가 합니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>

<span data-ttu-id="53aaa-105">복구 가능한 항목 폴더가 저장 제한에 도달 하면 사서함 기능은 다음과 같은 방식으로 영향을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="53aaa-106">사용자가 사서함에서 항목을 삭제할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="53aaa-107">관리 되는 폴더 도우미는 보존 태그 또는 관리 되는 폴더 설정을 기반으로 항목을 삭제할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="53aaa-108">단일 항목 복구를 사용 하도록 설정 하거나 보류 중인 사서함의 경우에는 쓰기 페이지 보호 프로세스에서 사용자가 편집한 항목의 버전을 유지 관리할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="53aaa-109">사서함 감사 로깅이 사용 하도록 설정 된 사서함의 경우 복구 가능한 항목 폴더의 감사 하위 폴더에는 사서함 감사 로그 항목을 저장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="53aaa-110">보류 중인 사서함의 경우 관리자는 Exchange Online PowerShell의 `Search-Mailbox -SearchDumpsterOnly -DeleteContent` 명령을 사용 하 여 복구 가능한 항목 폴더의 항목을 삭제할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="53aaa-111">자세한 내용은 다음 항목을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="53aaa-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="53aaa-112">메시지 검색 및 삭제</span><span class="sxs-lookup"><span data-stu-id="53aaa-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="53aaa-113">검색 사서함</span><span class="sxs-lookup"><span data-stu-id="53aaa-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="53aaa-114">보류 중인 사서함의 경우 관리자는 복구 가능한 항목 폴더에서 항목을 삭제 하기 전에 보류를 제거 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="53aaa-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="53aaa-115">자세한 내용은 [보류 중인 클라우드 기반 사서함의 복구 가능한 항목 폴더에서 항목 삭제](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="53aaa-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="53aaa-116">복구 가능한 항목 폴더가 가득 차지 않도록 하기 위해 관리자는 보류 중인 사서함에 대 한 복구 가능한 항목 폴더의 저장 제한을 증가 시켜 복구 가능한 항목 폴더의 항목을 사용자의 보관으로 이동 하는 사서함 보존 정책을 설정할 수 있습니다. 사서함별.</span><span class="sxs-lookup"><span data-stu-id="53aaa-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="53aaa-117">[보류 중인 사서함에 대 한 복구 가능한 항목 할당량 증가를](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="53aaa-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
