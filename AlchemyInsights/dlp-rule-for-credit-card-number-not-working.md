---
title: 신용 카드 번호에 대 한 DLP 규칙이 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932449"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="c313d-102">신용 카드 번호 관련 DLP 문제</span><span class="sxs-lookup"><span data-stu-id="c313d-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="c313d-103">**중요**: 많은 SharePoint Online 및 OneDrive 고객은 백그라운드에서 실행 되는 서비스에 대해 업무상 중요 한 응용 프로그램을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="c313d-104">이러한 서비스에는 콘텐츠 마이그레이션, DLP(데이터 손실 방지) 및 백업 솔루션이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="c313d-105">근래의 전례 없는 시간 동안 Microsoft는 원격 작업 시나리오에서 그 어느 때보다도 더 많이 서비스를 사용하는 귀사의 사용자를 위해 SharePoint Online 및 OneDrive 서비스가 계속 가용성 및 안정성을 유지하도록 보장하는 조치를 수행하겠습니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="c313d-106">Microsoft는 이 목표를 지원하고자 주중 낮 시간 동안 백그라운드 앱(마이그레이션, DLP 및 백업 솔루션)에 대해서 더욱 엄격한 제한을 구현하였습니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="c313d-107">따라서 이러한 시간대에는 이러한 앱의 처리량이 매우 제한적일 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="c313d-108">그러나 지역별로 오후와 주말 시간대에는 서비스가 백그라운드 앱의 크게 증가한 요청량을 처리할 준비를 갖추게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="c313d-109">**신용 카드 번호 관련 DLP 문제**</span><span class="sxs-lookup"><span data-stu-id="c313d-109">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="c313d-110">O365에서 DLP 중요 한 정보 유형을 사용할 때 **신용 카드 번호가** 포함 된 콘텐츠에 대해 **Dlp (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까?</span><span class="sxs-lookup"><span data-stu-id="c313d-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="c313d-111">이 경우에는 콘텐츠를 평가할 때 DLP 정책을 트리거하는 데 필요한 정보가 포함 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-111">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="c313d-112">예를 들어 신뢰 수준이 85% 인 **신용 카드 정책의** 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-112">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="c313d-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 서식이 있거나 서식이 없을 수 있는 16 자리 숫자 (dddddddddddddddd)로, Luhn 테스트를 통과 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="c313d-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** MasterCard, 검색 카드, JCB, 미국 익스프레스, 선물 카드 및 식사 권을 카드를 포함 하 여 전 세계 모든 주요 브랜드에서 카드를 검색 하는 매우 복잡 하 고 강력한 패턴입니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="c313d-115">**[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** 예, Luhn 체크섬</span><span class="sxs-lookup"><span data-stu-id="c313d-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="c313d-116">**[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 85% 확신 합니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="c313d-117">Func_credit_card 함수가 해당 패턴과 일치하는 콘텐츠를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-117">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="c313d-118">다음 중 하나가 충족됩니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-118">One of the following is true:</span></span>

  - <span data-ttu-id="c313d-119">Keyword_cc_verification의 키워드가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-119">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="c313d-120">Keyword_cc_name에서 키워드를 찾음</span><span class="sxs-lookup"><span data-stu-id="c313d-120">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="c313d-121">Func_expiration_date 함수가 올바른 날짜 형식의 날짜를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-121">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="c313d-122">체크섬 통과</span><span class="sxs-lookup"><span data-stu-id="c313d-122">The checksum passes</span></span>

    <span data-ttu-id="c313d-123">예를 들어 다음은 DLP 신용 카드 번호 정책을 트리거하는 예제입니다.</span><span class="sxs-lookup"><span data-stu-id="c313d-123">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="c313d-124"><: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="c313d-124">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="c313d-125">만료 날짜: 2/2009</span><span class="sxs-lookup"><span data-stu-id="c313d-125">Expires: 2/2009</span></span>

<span data-ttu-id="c313d-126">콘텐츠의 **신용 카드 번호** 를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 신용 카드 #에 대해 어떤 모양 인지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number) 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c313d-126">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="c313d-127">기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="c313d-127">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  