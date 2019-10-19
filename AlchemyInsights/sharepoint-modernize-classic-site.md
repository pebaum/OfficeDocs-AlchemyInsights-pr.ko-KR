---
title: 최신 사이트를 루트 사이트로
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid:
- "9000153"
- "1692"
ms.openlocfilehash: 6f55f1c63551027cc5522d296cb3f3f342356d95
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2019
ms.locfileid: "36576691"
---
# <a name="modernize-your-classic-sharepoint-site"></a><span data-ttu-id="7db07-102">클래식 SharePoint 사이트 Modernize</span><span class="sxs-lookup"><span data-stu-id="7db07-102">Modernize your classic SharePoint site</span></span>

<span data-ttu-id="7db07-103">최신 사용자 인터페이스로 전환 하려면 다음 사항을 중점적으로 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-103">To make the switch to a modern user interface, you need to focus on the following:</span></span>

- <span data-ttu-id="7db07-104">최신 사용자 인터페이스 (최신 목록 및 라이브러리 환경 이기도 함)를 사용 하도록 **목록 및 라이브러리** 를 전환 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-104">Transitioning your **lists and libraries** to use the modern user interface (also referred to as the modern list and library experience).</span></span>
- <span data-ttu-id="7db07-105">클래식 위 키 및 웹 파트 페이지의 **사이트 페이지** 를 최신 클라이언트 쪽 페이지로 변환</span><span class="sxs-lookup"><span data-stu-id="7db07-105">Transforming your **site pages** from classic wiki and web part pages into modern client-side pages.</span></span>
- <span data-ttu-id="7db07-106">**최신 사이트** 만들기 (팀 사이트 또는 커뮤니케이션 사이트)</span><span class="sxs-lookup"><span data-stu-id="7db07-106">Creating **modern sites** (Team site or Communication Site).</span></span>

<span data-ttu-id="7db07-107">사용자의 환경 Modernize:</span><span class="sxs-lookup"><span data-stu-id="7db07-107">Modernize your experience by:</span></span>
- <span data-ttu-id="7db07-108">사용자 지정 항목을 바꾸거나, 사용 된 보기에서 호환 되지 않는 열을 제거 하거나, 마지막 수단으로 데이터를 최신 사용자 인터페이스 호환 목록 형식으로 이동 하 여 [최신 사용자 인터페이스에 표시할 목록 및 라이브러리를 사용 하도록 설정](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries) 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-108">[Enabling lists and libraries to show in the modern user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries) by replacing customizations, removing incompatible columns from the used views, or (as a last resort) moving data into a modern user interface-compatible list type.</span></span>
- <span data-ttu-id="7db07-109">사이트를 [Office 365 그룹에 연결](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group)하 여 사이트에 최신 홈페이지를 제공 하 고 사이트에서 사서함 또는 Microsoft Planner와 같은 사용을 가능 하 게 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-109">[Connecting your site to an Office 365 group](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group), which gives your site a modern home page and enables your site to use, for example, a mailbox or Microsoft Planner.</span></span> <span data-ttu-id="7db07-110">이를 통해 최신 버전의 일정 및 작업 목록을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-110">This enables you to use a modern version of a calendar and task list.</span></span>
- <span data-ttu-id="7db07-111">[최신 페이지를 만들면](https://support.office.com/article/create-and-use-modern-pages-on-a-sharepoint-site-b3d46deb-27a6-4b1e-87b8-df851e503dec)이미지, Excel, Word 및 PowerPoint 문서, 비디오 등을 사용 하 여 아이디어를 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-111">[Creating modern pages](https://support.office.com/article/create-and-use-modern-pages-on-a-sharepoint-site-b3d46deb-27a6-4b1e-87b8-df851e503dec), is a great way to share ideas using images, Excel, Word and PowerPoint documents, video, and more.</span></span>
- <span data-ttu-id="7db07-112">[최신 클라이언트 쪽 페이지를 만들고](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-site-pages) 키를 클래식 위 키 및 웹 파트 페이지와 "유사" 하 게 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-112">[Creating modern client-side pages](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-site-pages) and configuring these to be "similar" to your key classic wiki and web part pages.</span></span> <span data-ttu-id="7db07-113">모든 페이지를 변환 하는 작업은 리소스 사용량이 많고 필요 하지 않은 경우에도 사이트의 주요 페이지에 대해 프로그래밍 페이지 변환을 수행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-113">Programmatic page transformation should be done for the key pages of your sites, as transforming all pages is resource-intensive and often not needed.</span></span> <span data-ttu-id="7db07-114">이 심사를 지원 하기 위해 SharePoint Modernization 스캐너가 현재 위 키 및 웹 파트 페이지에 대 한 사용 정보를 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7db07-114">To assist in this triage, the SharePoint Modernization scanner can give you usage information about the current wiki and web part pages.</span></span>
- <span data-ttu-id="7db07-115">[최신 사이트 만들기](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d)</span><span class="sxs-lookup"><span data-stu-id="7db07-115">[Creating modern sites](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span> <span data-ttu-id="7db07-116">팀 사이트 또는 커뮤니케이션 사이트를 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="7db07-116">Should I create a team site or a communication site?</span></span>

<span data-ttu-id="7db07-117">추가 정보:</span><span class="sxs-lookup"><span data-stu-id="7db07-117">Additional Info:</span></span> 
- <span data-ttu-id="7db07-118">클래식 SharePoint 사이트를 최신 환경에 현대화에 대 한 단계별 개요를 보려면 [Modernize the 클래식 Sharepoint 사이트](https://docs.microsoft.com/sharepoint/dev/transform/modernize-classic-sites)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="7db07-118">For a step-by-step overview of modernizing your classic SharePoint Sites to the modern experience, see [Modernize your classic SharePoint Sites](https://docs.microsoft.com/sharepoint/dev/transform/modernize-classic-sites).</span></span>
- <span data-ttu-id="7db07-119">[최신 환경](https://docs.microsoft.com/sharepoint/guide-to-sharepoint-modern-experience)에 대 한 가이드를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="7db07-119">See a guide to [Modern Experience](https://docs.microsoft.com/sharepoint/guide-to-sharepoint-modern-experience).</span></span>
- <span data-ttu-id="7db07-120">[SharePoint 클래식 및 현대적인 경험을](https://support.office.com/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="7db07-120">See [SharePoint Classic and Modern experiences](https://support.office.com/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f).</span></span> 




