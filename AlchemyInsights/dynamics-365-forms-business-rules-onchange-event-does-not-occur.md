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
ms.openlocfilehash: cbdedd2c5fcf5517243e60e36d86479d6c3f7814
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36529025"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>필드를 프로그래밍 방식으로 변경 하는 경우 OnChange 이벤트가 발생 하지 않음

필드가 특성을 사용 하 여 프로그래밍 방식으로 변경 되는 경우에는 *OnChange* 이벤트가 발생 하지 않습니다 *.* [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) 메서드 값을 설정한 후에 *OnChange* 이벤트에 대 한 이벤트 처리기를 실행 하려면 *formcontext 특성* 을 사용 해야 합니다. 코드의 [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) 메서드

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
