---
title: Dynamics 365 양식 비즈니스 규칙-양식에 대해 비즈니스 규칙이 발생 하지 않음
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748063"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a><span data-ttu-id="dbbf4-102">필드를 프로그래밍 방식으로 변경 하는 경우 OnChange 이벤트가 발생 하지 않음</span><span class="sxs-lookup"><span data-stu-id="dbbf4-102">OnChange event does not occur if the field is changed programmatically</span></span>

<span data-ttu-id="dbbf4-103">필드가 특성을 사용 하 여 프로그래밍 방식으로 변경 되는 경우에는 *OnChange* 이벤트가 발생 하지 않습니다 *.* [setValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) 메서드</span><span class="sxs-lookup"><span data-stu-id="dbbf4-103">The *OnChange* event does not occur if the field is changed programmatically using the *attribute.*[setValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) method.</span></span> <span data-ttu-id="dbbf4-104">값을 설정한 후에 *OnChange* 이벤트에 대 한 이벤트 처리기를 실행 하려면 *formcontext 특성* 을 사용 해야 합니다. 코드의 [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) 메서드</span><span class="sxs-lookup"><span data-stu-id="dbbf4-104">If you want event handlers for the *OnChange* event to run after you set the value you must use the *formContext.data.entity attribute.*[fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) method in your code.</span></span>

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
