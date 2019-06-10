---
title: DLP에 사용자 지정 형식이 필요할 수 있음
ms.author: stephow
author: stephow-MSFT
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 0ccdc524625ac76031004300a2406d5bfddcc759
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34770322"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="3186f-102">DLP에 사용자 지정 형식이 필요할 수 있음</span><span class="sxs-lookup"><span data-stu-id="3186f-102">DLP might need a custom type</span></span>

<span data-ttu-id="3186f-103">DLP (데이터 손실 방지) 정책을 사용 하 여 조직에서 중요 한 데이터를 식별 하 고 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-103">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="3186f-104">일부 시나리오에서는 조직의 데이터를 보호 하기 위해 **사용자 지정** 중요 한 정보 유형을 직접 만들어야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-104">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="3186f-105">예를 들어 조직에서 조직의 특정 형식으로 직원 Id 또는 기타 데이터를 식별 하 고 보호 해야 할 수 있습니다. 이 경우 자세한 내용은 다음 문서를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="3186f-105">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span> 
  
 <span data-ttu-id="3186f-106">**기본 제공 중요한 정보 유형 사용자 지정**</span><span class="sxs-lookup"><span data-stu-id="3186f-106">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="3186f-107">기본 제공 중요 한 정보 유형이 몇 가지 수단 만으로 요구 사항을 충족 하는 경우 [에는 기본 제공 중요 한 정보 유형을 사용자 지정할](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type)수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-107">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="3186f-108">예를 들어 키워드를 추가 또는 제거 하거나, 날짜나 주소와 같은 지원 증거를 추가 하거나 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-108">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="3186f-109">**사용자 지정 중요한 정보 유형 만들기**</span><span class="sxs-lookup"><span data-stu-id="3186f-109">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="3186f-110">그러나 서로 다른 유형의 중요 한 정보를 식별 하 고 보호 해야 하는 경우에는 보안 & 준수 센터의 UI에서 [사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-110">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span> 
  
<span data-ttu-id="3186f-111">**보안 & 준수 센터 PowerShell에서 사용자 지정 중요 한 정보 유형 만들기**</span><span class="sxs-lookup"><span data-stu-id="3186f-111">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="3186f-112">마지막으로 UI가 필요한 모든 옵션을 제공 하지 않는 경우 [보안 & 준수 센터 PowerShell에서 사용자 지정 중요 한 정보 유형을 만들](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell)수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-112">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="3186f-113">XML 파일을 시작 하 여 사용 가능한 모든 옵션을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3186f-113">By starting with an XML file, you can use every option available.</span></span>

    
