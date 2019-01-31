---
title: 암호 동기화 문제를 해결합니다
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 589820c945fb20f00431655f9f53196e740bb38f
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/30/2019
ms.locfileid: "29655817"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="78512-102">암호 동기화 문제를 해결합니다</span><span class="sxs-lookup"><span data-stu-id="78512-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="78512-103">문제를 해결 하려면 없는 암호는 Azure AD 연결 버전 1.1.614.0와 동기화 또는 이상:</span><span class="sxs-lookup"><span data-stu-id="78512-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="78512-104">**관리자 권한으로 실행** 옵션을 사용 하 여 Azure AD 연결 서버에서 새 Windows PowerShell 세션을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="78512-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="78512-105">**Set-executionpolicy RemoteSigned** 또는 **Set-executionpolicy 무제한**를 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="78512-106">Azure AD 연결 마법사를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="78512-107">이동은 \* \* 추가 작업 \* \* 페이지, \* \* Troubleshoot \* \*, **다음**을 클릭 하 고 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="78512-108">문제해결 페이지 PowerShell에서 **해결할 수 있습니다.를 시작 하려면 실행** 메뉴를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="78512-109">주 메뉴에서 **문제를 해결 하는 암호 동기화**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="78512-110">하위 메뉴에서 **암호 동기화 전혀 작동 하지 않습니다.** 를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="78512-111">**문제 해결 작업의 결과 이해**</span><span class="sxs-lookup"><span data-stu-id="78512-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="78512-112">문제해결 작업 다음 확인을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="78512-113">암호 동기화 기능 Azure AD 테 넌 트에 대해 사용 하도록 설정 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="78512-114">Azure AD 연결 서버 준비 모드에 있지 않음을 유효성을 검사 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="78512-115">각 커넥터에 대해 기존 온-프레미스 Active Directory (하는 기존 Active Directory 포리스트에 해당).</span><span class="sxs-lookup"><span data-stu-id="78512-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="78512-116">암호 동기화 기능을 사용 하도록 설정 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="78512-117">Windows 응용 프로그램 이벤트 로그에서 암호 동기화 하트 비트 이벤트를 검색합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="78512-118">온-프레미스 Active Directory 커넥터에서 각 Active Directory 도메인:</span><span class="sxs-lookup"><span data-stu-id="78512-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="78512-119">도메인에서 Azure AD 연결 서버에서 연결할 수 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="78512-120">온-프레미스 Active Directory 커넥터를 사용 하는 Active Directory 도메인 서비스 (AD DS) 계정에 올바른 사용자 이름, 암호 및 암호 동기화를 위해 필요한 사용 권한 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="78512-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="78512-121">암호 동기화 문제를 해결 하는 자세한 도움말을 [Azure AD 연결 동기화를 사용 하 여 해결 암호 동기화](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="78512-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  

