---
title: 독립 실행형 또는 기존 Office 설치를 사용 하 여 팀 배포
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 08/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 3318e1b17cc99e927e1011f7ca9eca8dec616d59
ms.sourcegitcommit: 4600dd4fb577bf5f5482a24616c2d9a6b81e8052
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054236"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>독립 실행형 또는 기존 Office 설치를 사용 하 여 팀 배포

Microsoft 팀은 이제 Office 365 ProPlus, Office 365 Business 및 Office for Mac을 ***새로 설치*** 하는 과정에 포함 됩니다. 자세한 내용은 [Microsoft 팀이 Office의 새 설치에 포함 될 때 시작 되는 시기](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus) 를 참조 하세요.

또한 월별 채널에서 버전 1906 부터는 기존 설치를 최신 버전으로 업데이트할 때 Windows를 실행 하는 장치에 대 한 Office 365 ProPlus (및 Office 365 Business)의 ***기존 설치에*** 팀이 추가 됩니다. 자세한 내용은 [Office의 기존 설치에 대 한](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus) 자세한 내용을 참조 하세요.

> [!NOTE]
> 이 롤아웃 일정을 기다리지 않으려면 [다음 지침](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) 을 수행 하 여 사용자에 대 한 독립 실행형으로 팀을 배포 하거나 사용자가 직접 팀을 설치 하도록 할 수 있습니다 [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).

조직이 팀을 배포할 준비가 되지 않은 경우 [신규](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) 또는 [기존](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) Office 설치에서 ***팀을 제외*** 하기 위해 수행할 수 있는 단계를 제공 합니다. 팀을 설치 하려고 하지만 사용자가 설치 된 후에 자동으로 시작 되지 않도록 하려면 [설치 후에 Microsoft 팀이 자동으로 시작 되지 못하도록](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation)합니다 .를 참조 하세요.

Windows를 실행 하는 장치에서 ***팀을 제거*** 하려면 [Microsoft 팀 제거](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81)를 참조 하세요. 여러 대상 컴퓨터나 사용자 로부터 Microsoft 팀을 정리 하려면 [Microsoft 팀 배포 정리](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up)를 참조 하세요.

공유 컴퓨터, RDS (원격 데스크톱 서비스) 또는 VDI (가상 데스크톱 인프라)를 사용 하는 경우에는 [공유 컴퓨터 및 vdi 환경을 Microsoft 팀과 함께](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams)참조 하십시오.

Mac 용 Office를 사용 하는 경우에 [는 mac에서 Microsoft 팀 설치](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac)를 참조 하세요.

> [!NOTE]
> 팀이 설치 된 후에는 새로운 기능과 품질 업데이트를 통해 약 2 주 동안 [자동으로 업데이트](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) 됩니다. 