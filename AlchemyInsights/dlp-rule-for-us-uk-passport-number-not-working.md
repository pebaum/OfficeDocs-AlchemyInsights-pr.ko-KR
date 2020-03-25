---
title: US/영국 여권 번호가 작동 하지 않는 DLP 규칙
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: c63e814059c897531109aa78725e9811b311fb27
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931268"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="f96c1-102">DLP-US/영국 여권 번호 관련 문제</span><span class="sxs-lookup"><span data-stu-id="f96c1-102">Problems with DLP - US/UK passport numbers</span></span>

<span data-ttu-id="f96c1-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="f96c1-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="f96c1-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="f96c1-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="f96c1-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="f96c1-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="f96c1-109">**US/영국 여권 번호와 관련 된 DLP 문제**</span><span class="sxs-lookup"><span data-stu-id="f96c1-109">**DLP issues with US/UK passport numbers**</span></span>

<span data-ttu-id="f96c1-110">O365에서 DLP 중요 한 정보 유형을 사용할 때 **US/영국 여권 번호가** 포함 된 콘텐츠에 대해 **Dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="f96c1-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK passport number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="f96c1-111">이 경우 콘텐츠를 평가할 때 필요한 DLP 정책에 대 한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-111">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="f96c1-112">예를 들어 **미국/영국 여권 번호** 정책의 신뢰 수준이 75% 인 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-112">For example, for a **US/UK passport number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="f96c1-113">**[형식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 9 자리 숫자</span><span class="sxs-lookup"><span data-stu-id="f96c1-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span>

- <span data-ttu-id="f96c1-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 9 자리 연속 숫자</span><span class="sxs-lookup"><span data-stu-id="f96c1-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="f96c1-115">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** 아니요, 체크섬이 없습니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="f96c1-116">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 75% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="f96c1-117">Func_usa_uk_passport 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-117">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="f96c1-118">Keyword_passport의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-118">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="f96c1-119">예를 들어 미국 여권 번호 123456789에 대 한 다음 샘플은 **US/영국 여권 번호** 정책에 대해 트리거됩니다.</span><span class="sxs-lookup"><span data-stu-id="f96c1-119">For example, the following sample would trigger for the **US/UK passport number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="f96c1-120">콘텐츠에 대 한 US/영국 여권 번호를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 US/Uk Passport 번호에 대해 어떻게 나타나는지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="f96c1-120">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="f96c1-121">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="f96c1-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  