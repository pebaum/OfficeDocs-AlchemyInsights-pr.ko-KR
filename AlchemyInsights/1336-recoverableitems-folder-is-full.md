---
title: 1336 RecoverableItems 폴더가 꽉
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: dbf4930c34e4175a14b77fab4eafc953bb37cc02
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29909294"
---
# <a name="the-recoverable-items-folder-is-full"></a>복구 가능한 항목 폴더 꽉 참

Office 365의 Exchange Online 사서함에 대 한 복구 가능한 항목 폴더에 대 한 기본 저장 용량 제한은 30GB입니다. 자동으로 복구 가능한 항목 폴더에 대 한 저장 용량 제한은 사서함 소송, eDiscovery 보류 중일 또는 Office 365 보존 정책에 할당 하는 경우에 100GB 증가 합니다.
  
복구 가능한 항목 폴더에 저장 용량 제한에 도달 하면, 사서함 기능이 다음과 같은 방법으로 적용 됩니다.
  
- 사용자는 사서함에서 항목을 삭제할 수 없습니다.
    
- 관리 되는 폴더 도우미는 보존 태그 또는 관리 되는 폴더 설정에 따라 항목을 삭제할 수 없습니다.
    
- 단일 항목 복구를 사용할 수 있거나 보류에 배치 되는 사서함에 대해 기록 중 복사 페이지 보호 프로세스는 사용자가 편집 하는 항목의 버전을 유지할 수 없습니다.
    
- 감사 로깅을 사용 하도록 설정 하는 사서함이 있는 사서함에 대 한 복구 가능한 항목 폴더의 감사 하위 폴더에 없는 사서함 감사 로그 항목을 저장할 수 있습니다.
    
보류에 없는 사서함에 대 한 관리자가 사용할 수는 `Search-Mailbox -SearchDumpsterOnly -DeleteContent` 복구 가능한 항목 폴더에서 항목을 삭제 하는 Exchange Online PowerShell에서 명령 합니다. 자세한 내용은 다음 항목을 참조 하십시오. 
  
- [메시지 검색 및 삭제](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
보류에 있는 사서함에 대해 관리자가 복구 가능한 항목 폴더에서 삭제 된 항목을 수행할 수 있습니다 전에 보류를 제거 해야 합니다. 자세한 내용은 [폴더에 있는 클라우드 기반 사서함의 대기 복구 가능한 항목에서 항목을 삭제](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold)를 참조 하십시오.
  
차게에서 복구 가능한 항목 폴더를 방지 하려면 관리자가 복구 가능한 항목 폴더에 있는 사서함에 대 한 유지 하 고 사용자의 보관 사서함을 복구 가능한 항목 폴더에서 항목을 이동 하는 사서함 보존 정책을 설정의 저장 용량 제한 늘릴 수 있습니다. 사서함입니다. [증가에 있는 사서함에 대 한 할당량 대기 복구 가능한 항목을](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold)참조 하십시오.
  

