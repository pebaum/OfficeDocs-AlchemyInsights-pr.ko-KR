---
title: 암호 동기화 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 1320c0fe839337188162824439be6f15f86b6c90
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32390438"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="d9e91-102">암호 동기화 문제 해결</span><span class="sxs-lookup"><span data-stu-id="d9e91-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="d9e91-103">Azure AD Connect 버전 1.1.614.0 이상으로 암호가 동기화 되지 않는 문제를 해결 하려면 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="d9e91-104">**관리자 권한으로 실행** 옵션을 사용 하 여 Azure AD Connect 서버에서 새 Windows PowerShell 세션을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="d9e91-105">**ExecutionPolicy RemoteSigned** 또는 **ExecutionPolicy 제한이**없는 경우 실행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="d9e91-106">Azure AD Connect 마법사를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="d9e91-107">\* \* 추가 작업 \* \* 페이지로 이동 하 여 \* \* 문제 해결 \* \*을 선택 하 고 **다음**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="d9e91-108">문제 해결 페이지에서 **시작을 클릭 하 여 PowerShell에서 문제 해결** 메뉴를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="d9e91-109">주 메뉴에서 **암호 동기화 문제 해결**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="d9e91-110">하위 메뉴에서 **암호 동기화가 전혀 작동 하지**않습니다 .를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="d9e91-111">**문제 해결 작업 결과 이해**</span><span class="sxs-lookup"><span data-stu-id="d9e91-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="d9e91-112">문제 해결 작업에서는 다음 검사를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="d9e91-113">Azure AD 테 넌 트에 대해 암호 동기화 기능이 사용 하도록 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="d9e91-114">Azure AD Connect 서버가 준비 모드에 있지 않은지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="d9e91-115">기존 온-프레미스 active directory 커넥터 (기존 active directory 포리스트에 해당)에 대해 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="d9e91-116">암호 동기화 기능이 사용 하도록 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="d9e91-117">Windows 응용 프로그램 이벤트 로그에서 암호 동기화 하트 비트 이벤트를 검색 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="d9e91-118">온-프레미스 active directory 커넥터 아래의 각 Active directory 도메인에 대해 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="d9e91-119">Azure AD Connect 서버에서 도메인에 연결할 수 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="d9e91-120">온-프레미스 Active directory 커넥터에서 사용 하는 AD DS (Active directory 도메인 서비스) 계정이 암호 동기화에 필요한 올바른 사용자 이름, 암호 및 사용 권한을가지고 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="d9e91-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="d9e91-121">암호 동기화 문제 해결에 대 한 자세한 내용은 [Azure AD Connect sync를 사용한 암호 동기화 문제 해결](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d9e91-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  

