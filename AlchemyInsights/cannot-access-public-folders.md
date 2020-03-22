---
title: 공용 폴더에 액세스할 수 없음
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891755"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Outlook에서 공용 폴더에 연결할 수 없음

일부 사용자가 공용 폴더 액세스가 작동 하지 않는 경우 다음을 시도해 보세요.

EXO PowerShell에 연결 하 고 문제 사용자 계정에 대해 DefaultPublicFolderMailbox 매개 변수를 구성 하 여 작업 중인 사용자 계정의 매개 변수와 일치 시킵니다.

예제:

Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox, EffectivePublicFolderMailbox

Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<값을 이전 명령>에서

변경 내용이 적용 되려면 한 시간 이상 기다립니다.

문제가 계속 되 면 다음 [절차](https://aka.ms/pfcte) 에 따라 Outlook을 사용 하 여 공용 폴더 액세스 문제를 해결 하세요.