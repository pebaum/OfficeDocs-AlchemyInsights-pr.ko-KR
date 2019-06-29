---
title: SharePoint 또는 OneDrive에서 항목을 삭제할 수 없음
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: d25214f26a3168e3e350b5cc31ca870e65d48ad9
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35366539"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="d5aa8-102">항목을 삭제할 수 없음</span><span class="sxs-lookup"><span data-stu-id="d5aa8-102">Unable to delete items</span></span>

<span data-ttu-id="d5aa8-103">항목을 삭제 하는 데 문제가 있나요?</span><span class="sxs-lookup"><span data-stu-id="d5aa8-103">Having issues deleting items?</span></span>

- <span data-ttu-id="d5aa8-104">항상 항목을 삭제 하거나 [사이트 모음 관리자](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) 가 항목을 제거할 수 있는 [적절 한 권한이](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d5aa8-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="d5aa8-105">해당 항목에 대 한 [보존 정책](https://docs.microsoft.com/office365/securitycompliance/retention-policies) 설정이 없는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d5aa8-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="d5aa8-106">항목이 다른 사용자에 게 [체크 아웃](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) 되지 않았는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d5aa8-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="d5aa8-107">마지막으로 관리자는 stubborn 항목 강제 삭제와 같은 복잡 한 관리 작업을 수행 하는 데 사용할 수 있는 PowerShell 명령 라이브러리가 포함 된 [SharePoint 패턴 및 사례](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP)를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d5aa8-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="d5aa8-108">PNP 파일 제거</span><span class="sxs-lookup"><span data-stu-id="d5aa8-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="d5aa8-109">PNP 폴더 제거</span><span class="sxs-lookup"><span data-stu-id="d5aa8-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="d5aa8-110">PNP 목록 항목 제거</span><span class="sxs-lookup"><span data-stu-id="d5aa8-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="d5aa8-111">PNP 목록 제거</span><span class="sxs-lookup"><span data-stu-id="d5aa8-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="d5aa8-112">PNP 필드 제거 (열)</span><span class="sxs-lookup"><span data-stu-id="d5aa8-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)