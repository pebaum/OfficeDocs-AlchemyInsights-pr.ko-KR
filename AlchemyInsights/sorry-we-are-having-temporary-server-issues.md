---
title: Office 앱을 수정 하는 동안 일시적인 서버 문제 메시지가 발생 합니다.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627996"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="616d4-102">Office 앱 문제 해결 "죄송 하지만 일시적인 서버 문제가 발생 합니다." 메시지</span><span class="sxs-lookup"><span data-stu-id="616d4-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="616d4-103">이 메시지가 표시 되 면 다음을 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="616d4-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="616d4-104">방화벽, 바이러스 백신 소프트웨어 및 프록시 설정을 확인 하 여 Office 앱에 대 한 인터넷 액세스를 차단 하 고 있지 않은지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="616d4-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="616d4-105">[Office 365 url 및 IP 주소 범위](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="616d4-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="616d4-106">**실행** **시작** > 으로 이동한 다음 services.msc를 입력 **합니다.**</span><span class="sxs-lookup"><span data-stu-id="616d4-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="616d4-107">다음 서비스가 모두 실행 중인지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="616d4-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="616d4-108">네트워크 연결 장치 자동 설정</span><span class="sxs-lookup"><span data-stu-id="616d4-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="616d4-109">네트워크 목록 서비스</span><span class="sxs-lookup"><span data-stu-id="616d4-109">Network List Service</span></span>
    - <span data-ttu-id="616d4-110">네트워크 위치 인식</span><span class="sxs-lookup"><span data-stu-id="616d4-110">Network Location Awareness</span></span>
    - <span data-ttu-id="616d4-111">Windows 이벤트 로그</span><span class="sxs-lookup"><span data-stu-id="616d4-111">Windows Event Log</span></span>

<span data-ttu-id="616d4-112">이러한 서비스 중 하나가 실행 되 고 있지 않으면 시작 해 봅니다.</span><span class="sxs-lookup"><span data-stu-id="616d4-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="616d4-113">서비스를 시작 하는 데 문제가 있는 경우 상승 된 권한으로 명령 프롬프트를 열어 다음 명령을 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="616d4-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="616d4-114">**sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="616d4-114">**sfc /scannow**</span></span>

<span data-ttu-id="616d4-115">이 명령이 완료 되 면 컴퓨터를 다시 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="616d4-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="616d4-116">자세한 내용은 ["미안 하지만 사용자의 계정에 연결할 수 없습니다."를 참조 하세요. 나중에 다시 시도 하세요. "Office 365에서 Office를 정품 인증 하는 동안 오류가 발생 했습니다](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="616d4-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>