---
title: SharePoint Online에서 사이트 만들기
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 458990889d3c074820527982cbfa6e2d198d3e66
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052475"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="6b757-102">템플릿을 사용 하 여 SharePoint 사이트 만들기</span><span class="sxs-lookup"><span data-stu-id="6b757-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="6b757-103">SharePoint 사이트 서식 파일은 특정 비즈니스 요구를 중심으로 디자인 된 미리 만들어진 정의입니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="6b757-104">자세한 내용은 [서식 파일을 사용 하 여 여러 종류의 SharePoint 사이트 만들기](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="6b757-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="6b757-105">다음은 Sharepoint Online에서 사이트 또는 목록을 서식 파일로 저장 하는 방법에 대 한 몇 가지 일반적인 문제/해결 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="6b757-106">**사이트 저장/목록 서식 파일 단추를 사용할 수 없거나 누락 되었습니다.**</span><span class="sxs-lookup"><span data-stu-id="6b757-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="6b757-107">관리자는 서식 파일 기능을 사용 하도록 설정 하기 위해 사용자 지정 스크립트를 허용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="6b757-108">자세한 단계는 예 및 고려 사항 참조</span><span class="sxs-lookup"><span data-stu-id="6b757-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="6b757-109">사용자 지정 스크립트 허용 또는 금지</span><span class="sxs-lookup"><span data-stu-id="6b757-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="6b757-110">사이트를 서식 파일로 저장 명령은 지원 되지 않으며 SharePoint Server 게시 인프라를 사용 하는 사이트에서 문제를 발생 시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="6b757-111">**사이트 서식 파일을 만들 수 없거나 제대로 작동 하지 않음**</span><span class="sxs-lookup"><span data-stu-id="6b757-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="6b757-112">서식 파일에 [기능이](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) 누락 되었거나 활성화 되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="6b757-113">현재 사이트 모음에서 정품 인증 기능을 사용할 수 없는 경우에는 사이트 서식 파일을 사용 하 여 사이트를 만들 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="6b757-114">목록 또는 라이브러리가 사이트 서식 파일의 생성을 차단할 수 있는 것으로 표시 되는 것으로 5000 항목의 [목록이](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 나 라이브러리를 초과 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="6b757-115">사이트에서 너무 많은 리소스를 사용 하 고 있기 때문에 사이트 서식 파일이 50 MB 제한을 초과 합니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="6b757-116">조회 열을 사용 하는 목록의 데이터를 표시 하는 데 문제가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6b757-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="6b757-117">자세한 내용은 [Template 생성 목록에서 SharePoint Online의 올바른 조회 목록의 데이터를 표시 하지 않습니다](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="6b757-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="6b757-118">일반적인 문제와 솔루션에 대 한 자세한 내용은 [사이트 서식 파일 만들기 및 사용](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)을 확인 하세요.</span><span class="sxs-lookup"><span data-stu-id="6b757-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



