---
title: 터미널 서버에 office를 설치 하는 문제에 대 한 해결 방법
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 85f24284-af6f-4624-b6be-901a4a9206eb
ms.openlocfilehash: 6e877493f44b4636e1293582b5baf6bf98d1d251
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32373718"
---
# <a name="solutions-for-issues-around-installing-office-on-a-terminal-server"></a><span data-ttu-id="b237c-102">터미널 서버에 office를 설치 하는 문제에 대 한 해결 방법</span><span class="sxs-lookup"><span data-stu-id="b237c-102">Solutions for issues around installing office on a Terminal Server</span></span>

<span data-ttu-id="b237c-103">공유 컴퓨터 활성화를 사용 하려면 office 365 ProPlus를 포함 하는 office 365 요금제가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-103">To use shared computer activation, you must have an Office 365 plan that includes Office 365 ProPlus.</span></span>
  
- <span data-ttu-id="b237c-104">Office 365 ProPlus에 대해 공유 컴퓨터 활성화가 사용 하도록 설정 되어 있는지 확인</span><span class="sxs-lookup"><span data-stu-id="b237c-104">Verify that shared computer activation is enabled for Office 365 ProPlus</span></span>
    
- <span data-ttu-id="b237c-105">Office 365 ProPlus에 대 한 정품 인증 성공 확인</span><span class="sxs-lookup"><span data-stu-id="b237c-105">Verify that activation for Office 365 ProPlus succeeded</span></span>
    
- <span data-ttu-id="b237c-106">공유 컴퓨터 활성화에 대 한 오류 메시지를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-106">Review error messages for shared computer activation:</span></span>
    
  - <span data-ttu-id="b237c-107">"사용자의 계정에서 찾은 제품은 공유 컴퓨터 시나리오에서 Office를 정품 인증 하는 데 사용할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="b237c-107">"The products we found in your account cannot be used to activate Office in shared computer scenarios"</span></span>
  
<span data-ttu-id="b237c-108">이 오류는 office 365 ProPlus를 포함 하는 office 365 요금제가 없다는 것을 의미 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-108">This error means that you don't have an Office 365 plan that includes Office 365 ProPlus.</span></span>
    
  - <span data-ttu-id="b237c-109">"허가 되지 않은 제품"</span><span class="sxs-lookup"><span data-stu-id="b237c-109">"Unlicensed Product"</span></span>
    
  - <span data-ttu-id="b237c-110">사용자에 게 Office 365 ProPlus에 대 한 라이선스가 할당 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-110">Check that the user is assigned a license for Office 365 ProPlus.</span></span>
    
  - <span data-ttu-id="b237c-111">사용자가 Office 365에 대 한 사용자 계정으로 로그인 했는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-111">Check that the user signs in with her user account for Office 365</span></span>
    
  - <span data-ttu-id="b237c-112">공유 컴퓨터와 인터넷 사이에 연결이 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="b237c-112">Check that there is connectivity between the shared computer and the Internet.</span></span>
    
<span data-ttu-id="b237c-113">기타 문제 해결 팁에 대 한 자세한 내용은 [Office 365 ProPlus에 대 한 공유 컴퓨터 정품 인증과 관련 된 문제 해결](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus) 을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="b237c-113">For other troubleshooting tips, please see: [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus)</span></span>
  

