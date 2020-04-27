---
title: 포털에 누락된 Configuration Manager 장치
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789907"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a>포털에 누락된 Configuration Manager 장치

장치 동기화가 작동하려면 서비스 연결 지점 역할을 호스팅하는 온-프레미스 서버에서 [필수 인터넷 끝점](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints)을 연결할 수 있어야 합니다. 장치 동기화 문제를 해결하려면 서비스 연결 지점에 있는 **CMGatewaySyncUploadWorker.log**를 검토하세요.

[Microsoft 끝점 관리자에서 테넌트 연결](https://docs.microsoft.com/configmgr/tenant-attach/)에 대해서 자세히 알아보세요.
