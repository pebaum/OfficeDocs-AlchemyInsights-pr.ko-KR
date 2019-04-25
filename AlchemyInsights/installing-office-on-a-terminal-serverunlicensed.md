---
title: 터미널 서버에 office 설치-사용 허가 되지 않음
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 971edd9c064b448446ba16361e99df4a2291c14f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32410128"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="bd641-102">터미널 서버에 Office 설치</span><span class="sxs-lookup"><span data-stu-id="bd641-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="bd641-103">RDS (원격 데스크톱 서비스)를 사용 하 여 Windows Server에 Office 365 ProPlus를 배포 하는 경우 (이전의 터미널 서비스:</span><span class="sxs-lookup"><span data-stu-id="bd641-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="bd641-104">office 365 Enterprise E3 또는 Enterprise e 5와 같은 office 365 ProPlus를 포함 하는 office 365 요금제가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="bd641-105">office 365 business 및 office 365 business Premium 요금제에는 office 365 ProPlus가 포함 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
    
- <span data-ttu-id="bd641-106">[공유 컴퓨터 활성화](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)를 사용 하도록 설정 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>
    
<span data-ttu-id="bd641-107">office 365 portal에서 RDS에 office 365 ProPlus를 설치 하려면 \* \* *기본 설치 설정을 사용 하는* 경우에는 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span> 
  
1. <span data-ttu-id="bd641-108">보유 하 고 있는 Office 365 요금제를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-108">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="bd641-109">방법 알아보기</span><span class="sxs-lookup"><span data-stu-id="bd641-109">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)
    
2. <span data-ttu-id="bd641-110">필요한 경우 다른 Office 365 요금제로 전환 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-110">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="bd641-111">방법 알아보기</span><span class="sxs-lookup"><span data-stu-id="bd641-111">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)
    
3. <span data-ttu-id="bd641-112">office가 다른 office 365 계획을 사용 하 여 RDS 서버에 이미 설치 되어 있는 경우에는 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-112">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="bd641-113">예를 들어 제어판으로 이동 하 여 \> 프로그램을 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-113">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="bd641-114">문제가 발생 하는 경우 [Microsoft 지원 및 복구 도우미를](https://aka.ms/SARA-OfficeUninstall-Alchemy) 사용 하 여 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-114">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span> 
    
4. <span data-ttu-id="bd641-115">RDS 서버에서 관리자 계정을 사용 하 여 office 365 포털에 로그인 하 고 [office 365 ProPlus를 설치](https://portal.office.com/OLS/MySoftware.aspx)합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
    
5. <span data-ttu-id="bd641-116">office 설치 후 \* \* office 응용 프로그램에 대해 \* \*를 *열거나 로그온 하지 않습니다* .</span><span class="sxs-lookup"><span data-stu-id="bd641-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span> 
    
6. <span data-ttu-id="bd641-117">RDS 서버에서 다음 단계를 수행 하 여 레지스트리를 편집 하 여 공유 컴퓨터 활성화를 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
    
1. <span data-ttu-id="bd641-118">화면 왼쪽 아래에 있는 Windows 단추를 마우스 오른쪽 단추로 클릭 하 고 실행을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-118">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="bd641-119">열기 상자에 **regedit**를 입력 하 고 확인을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-119">In the Open box, type **regedit**, and then select OK.</span></span> 
    
2. <span data-ttu-id="bd641-120">레지스트리 편집기를 사용 하 여 장치를 변경할 수 있는지 묻는 메시지가 표시 되 면 예를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>
    
3. <span data-ttu-id="bd641-121">레지스트리 편집기에서 HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration. 아래에 설정 1을 사용 하 여 **sharedcomputerlicensing** 의 문자열 값을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span> 
    
7. <span data-ttu-id="bd641-122">RDS 서버에서 \* \* \*최종 사용자 \* *로 로그인* 하 여 [Office 365 ProPlus에 대해 공유 컴퓨터 활성화가 사용 하도록 설정 되어 있는지 확인](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded)합니다.</span><span class="sxs-lookup"><span data-stu-id="bd641-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
    
<span data-ttu-id="bd641-123">office 배포 도구를 사용 하 여 필수 구성 요소, 설치 지침 및 사용자 지정 설치에 대 한 지침에 대 한 자세한 내용은 [원격 데스크톱 서비스를 사용 하 여 office 365 ProPlus 배포](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="bd641-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="bd641-124">공유 컴퓨터 활성화와 관련 된 오류를 해결 하려면 [Office 365 ProPlus에 대 한 공유 컴퓨터 활성화의 문제 해결](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="bd641-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  

