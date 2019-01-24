---
title: 전자 메일 메시지를 보관 사서함으로 이동
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 41d6825b568263fb7b09066b65235aa348415bae
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/24/2019
ms.locfileid: "29478247"
---
문제가 보관 사서함에 항목을 보관 합니다. 다음 단계를 수행 했는지 확인 합니다.
  
1. **사서함 보관** 활성화 되었는지 확인 합니다. 그렇지 않은 경우에 [이](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) 문서의 단계를 사용 하 여 보관 사서함을 사용 하도록 설정 합니다. 
    
2. Exchange 관리 센터에서 **준수 관리**에서 **보존 태그** 선택, 원하는 **보존 기간**을 포함 하는 **보관 함으로 이동** 작업으로 **보존 태그** 를 만듭니다.
    
3. Exchange 관리 센터에서 **보존 정책**을 선택 하 고 **보존 정책** 을 만들고 해당 정책에 **보관 사서함으로 이동** 보존 태그에 추가 합니다. 
    
4. 특정 사용자의 사서함에 [보존 정책을 할당](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) 합니다. 동일한 정책은는 **기본** 및 **보관** 사서함에 모두 적용 됩니다. 
    
이제 사용자의 사서함 항목 보관 사서함을 이동 하는 보관 정책이 있어야 합니다. 관리 되는 폴더 도우미 (MFA)를 실행 하 고 사용자의 사서함에 새 설정을 적용 하려면 강제로 할 수도 있습니다. 관리 되는 폴더 도우미가 특정 사서함에 대 한 시작 하려면 [EXO PowerShell에 연결](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) 하는 동안 다음 명령을 실행 합니다. 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

보관 정책 설정에 대 한 자세한 내용을 확인 하려면 [사서함에 대 한 보관 및 삭제 정책 설정](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)를 참조 하십시오.
  

