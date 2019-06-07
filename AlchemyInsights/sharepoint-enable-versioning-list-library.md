---
title: 목록 또는 라이브러리에서 버전 관리 사용
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: a84868ba-7657-4f34-8a57-df9c6f9732dc
ms.openlocfilehash: d9adb02292132e60af206e2fd7fe3204ff03471f
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760521"
---
# <a name="enable-versioning-for-a-sharepoint-list-or-library"></a><span data-ttu-id="62265-102">SharePoint 목록 또는 라이브러리에 대해 버전 관리를 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="62265-102">Enable versioning for a SharePoint list or library</span></span>


<span data-ttu-id="62265-103">SharePoint 목록 또는 라이브러리에서 버전 관리를 사용 하도록 설정 하면 목록 및 파일을 변경할 때마다 라이브러리의 항목을 저장, 추적 및 복원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="62265-103">When versioning is enabled in your SharePoint list or library, you can store, track, and restore items in a list and files in a library whenever they change.</span></span> <span data-ttu-id="62265-104">버전 관리를 체크 아웃과 같은 다른 설정과 함께 사용 하면 사이트에 게시 되는 콘텐츠를 제어할 수 있으며 이전 버전의 항목 또는 파일을 확인 하거나 복원 해야 하는 경우 실제 가치를 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="62265-104">Versioning, combined with other settings, such as checkout, gives you a lot of control of the content that is posted on your site and can provide real value if you ever have a need to look at or restore an old version of an item or file.</span></span>

<span data-ttu-id="62265-105">버전 관리에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="62265-105">For more information on versioning please visit the below articles.</span></span>

[<span data-ttu-id="62265-106">SharePoint 목록 또는 라이브러리에서 버전 관리를 사용 하는 방법</span><span class="sxs-lookup"><span data-stu-id="62265-106">How does versioning work in a SharePoint list or library</span></span>](https://support.office.com/article/how-does-versioning-work-in-a-sharepoint-list-or-library-0f6cd105-974f-44a4-aadb-43ac5bdfd247)

[<span data-ttu-id="62265-107">목록 또는 라이브러리의 버전 관리 설정 및 구성</span><span class="sxs-lookup"><span data-stu-id="62265-107">Enable and configure versioning for a list or library</span></span>](https://support.office.com/article/enable-and-configure-versioning-for-a-list-or-library-1555d642-23ee-446a-990a-bcab618c7a37?ocmsassetID=HA102772148&amp;CTT=3&amp;CorrelationId=52441bb1-a619-4375-89d5-19d28769890f&amp;ui=en-US&amp;rs=en-US&amp;ad=US)

[<span data-ttu-id="62265-108">버전 기록을 보는 방법</span><span class="sxs-lookup"><span data-stu-id="62265-108">How to view version history</span></span>](https://support.office.com/article/View-the-version-history-of-an-item-or-file-in-a-list-or-library-53262060-5092-424D-A50B-C798B0EC32B1)

[<span data-ttu-id="62265-109">OneDrive에서 이전 버전의 파일 복원</span><span class="sxs-lookup"><span data-stu-id="62265-109">Restore a previous version of a file in OneDrive</span></span>](https://support.office.com/article/restore-a-previous-version-of-a-file-in-onedrive-159cad6d-d76e-4981-88ef-de6e96c93893?ui=en-US&amp;rs=en-US&amp;ad=US)

[<span data-ttu-id="62265-110">이전 버전의 Office 파일 보기</span><span class="sxs-lookup"><span data-stu-id="62265-110">View previous versions of Office files</span></span>](https://support.office.com/article/view-previous-versions-of-office-files-5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

[<span data-ttu-id="62265-111">버전 관리 제한</span><span class="sxs-lookup"><span data-stu-id="62265-111">Versioning limits</span></span>](https://docs.microsoft.com/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits)

<span data-ttu-id="62265-112">참고: Office 365 고객은 새 비즈니스용 OneDrive 라이브러리를 만들 때 기본적으로 버전 관리를 설정 하 고 마지막 500 버전의 문서를 자동으로 저장 합니다.</span><span class="sxs-lookup"><span data-stu-id="62265-112">Note: If you are an Office 365 customer, versioning is now turned on by default when you create new OneDrive for Business libraries, and it will automatically save the last 500 versions of a document.</span></span> <span data-ttu-id="62265-113">이렇게 하면 중요 한 문서나 데이터가 손실 되는 것을 방지할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="62265-113">This will help you prevent losing important documents or data.</span></span> <span data-ttu-id="62265-114">비즈니스용 OneDrive 사이트 또는 버전 관리를 사용 하지 않는 팀 사이트에 기존 라이브러리가 있으면 언제 든 지 해당 사용자에 대해 버전 관리를 해제할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="62265-114">If you have existing libraries on your OneDrive for Business site or on your team site that do not have versioning enabled, you can turn versioning on for them at any time.</span></span>


