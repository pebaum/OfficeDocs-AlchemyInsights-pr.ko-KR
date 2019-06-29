---
title: 보관 사서함으로 전자 메일 메시지 이동
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: a29fb799b68f5c187ca1d44aeaf94e6cd8760b0e
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35379503"
---
# <a name="move-email-to-the-archive-mailbox"></a>보관 사서함으로 전자 메일 이동

1. **보관 사서함** 이 사용 하도록 설정 되었는지 확인 합니다. 그렇지 않으면 [이 문서의](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) 단계를 사용 하 여 보관 사서함을 사용 하도록 설정 합니다.

2. 보관 사서함에 메시지를 자동으로 보관 하려면 **보관 함으로 이동** 작업이 있는 보존 태그가 **전체 사서함에 자동으로 적용 (기본값) 태그**를 설정 해야 합니다. 여기에 나오는 단계를 사용 하 여 [Default To Archive 태그](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0)를 만듭니다.

3. 다음으로, **보관** 태그를 보존 정책에 추가 합니다. Exchange 관리 센터에서 **보존 정책을** 선택 하 > > **저장**을 통해 **보관 함으로 이동 태그** 를 정책에 추가 합니다.

4. 이제 특정 사용자의 사서함에 [보존 정책을 할당](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) 합니다. **기본** 및 **보관** 사서함 모두에 동일한 정책이 적용 됩니다.

MFA (관리 되는 폴더 도우미)를 강제로 실행 하 고 사용자 사서함에 새 설정을 적용 해야 할 수 있습니다. [EXO PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) 된 동안 다음 명령을 실행 하 여 특정 사서함에 대해 관리 되는 폴더 도우미를 시작 합니다.
  
Start-ManagedFolderAssistant-Identity<name of the mailbox>

보관 정책 설정에 대 한 자세한 내용은 [사서함에 대 한 보관 및 삭제 정책](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)설정을 참조 하십시오.
  