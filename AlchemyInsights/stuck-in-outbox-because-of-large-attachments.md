---
title: 대용량 첨부 파일 때문에 보낼 편지함에서 중지
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232636"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>보낼 편지함에 걸린 메시지 수정

영향을 받는 시스템의 [Microsoft 지원 및 복구 도우미](https://diagnostics.office.com/#/) 도구에서 ["전자 메일 메시지를 보내거나 받거나 찾는 데 문제가](https://aka.ms/SaRA-OutlookSendReceive) 있습니다." 시나리오를 실행 하 여 시작 하는 것이 좋습니다.

메시지가 보낼 편지함에 걸려 있으면 첨부 파일이 크거나 "연결 되 면 즉시 보내기" 옵션이 설정 되어 있지 않은 것입니다.

**큰 첨부 파일 제거**

1. **보내기/받기를** > **오프 라인으로 작업**을 클릭 합니다. 
2. 탐색 창에서 **보낼 편지함**을 클릭 합니다. 여기서는 다음을 수행할 수 있습니다. 
    - 메시지를 삭제 합니다. 선택 하 고 **삭제**를 클릭 하면 됩니다.
    - 메시지를 **임시 보관 함 폴더로**끌어 온 후 메시지를 두 번 클릭 하 여 열고, 첨부 파일을 클릭 한 다음 **삭제**를 클릭 합니다.
3. Outlook에서 메시지 전송을 시도 하는 오류 메시지가 나타나면 Outlook을 닫습니다. 종료 하는 데 몇 분 정도 걸릴 수 있습니다. Outlook이 닫히지 않으면 **Ctrl + Alt + delete** 를 누르고 **작업 관리자 시작**을 클릭 합니다. 작업 관리자에서 **프로세스** 탭을 선택 하 고 outlook .exe로 스크롤한 다음 **프로세스 끝내기**를 클릭 합니다.
4. Outlook을 닫은 후 Outlook을 다시 시작 하 고 2-3 단계를 반복 합니다. 
5. 첨부 파일을 제거한 후에는**오프 라인으로 작업** **보내기/받기를** > 클릭 하 여 단추를 선택 취소 하 고 온라인 작업을 다시 시작 합니다. 

또한 **보내기를**클릭 했지만 연결 되어 있지 않은 경우에도 보낼 편지함에 메시지가 남아 있습니다. **보내기/받기를** 클릭 하 고 **오프 라인으로 작업** 단추를 확인 합니다. 파란색 이면 연결 되어 있지 않은 것입니다. 단추를 클릭 하 여 연결 (단추가 흰색으로 바뀜) 하 고 **모두 보내기를**클릭 합니다.
 
**연결 되 면 즉시 보내기 사용**
 
1. 파일 탭에서 **옵션**을 클릭합니다.

2. Outlook 옵션 대화 상자에서 **고급**을 클릭 합니다.

3. 보내기 및 받기 섹션에서 **연결 되 면 즉시 보내기를**사용 하도록 설정 합니다. **확인**을 클릭합니다.
 
자세한 내용은 다음을 참조 하십시오.
- [비디오: 걸린 전자 메일 보내기 또는 삭제](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [Outlook에서 보내기/받기 작업을 수동으로 시작할 때까지 전자 메일이 보낼 편지함 폴더에 남아 있습니다.](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
