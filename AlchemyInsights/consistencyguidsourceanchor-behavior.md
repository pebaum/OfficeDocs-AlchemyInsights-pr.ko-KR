---
title: ConsistencyGuid/sourceanchor 동작
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: cb1b50792b07a1b3b69607bf2f6824141a15922f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32408114"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="df784-102">ConsistencyGuid/sourceanchor 동작</span><span class="sxs-lookup"><span data-stu-id="df784-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="df784-103">Azure AD Connect (버전 1.1.524.0 and after)를 이제 msds-alloweddnssuffixesexadnomk-ConsistencyGuid를 sourceanchor 특성으로 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="df784-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="df784-104">이 기능을 사용 하는 경우 Azure AD Connect에서는 자동으로 동기화 규칙을 다음과 같이 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="df784-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="df784-105">사용자 개체의 sourceanchor 특성으로 msds-alloweddnssuffixesexadnomk-ConsistencyGuid을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="df784-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="df784-106">ObjectGUID는 다른 개체 형식에 사용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="df784-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="df784-107">msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성이 채워지지 않는 지정 된 온-프레미스 AD 사용자 개체의 경우 Azure AD Connect는 해당 objectGUID 값을 온-프레미스 Active Directory의 msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성에 다시 씁니다.</span><span class="sxs-lookup"><span data-stu-id="df784-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="df784-108">msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성이 채워지면 azure ad Connect에서이 개체를 azure ad로 내보냅니다.</span><span class="sxs-lookup"><span data-stu-id="df784-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="df784-109">**참고:** 온-프레미스 ad 개체를 Azure ad Connect로 가져온 후 (AD 커넥터 공간으로 가져오고 메타 버스에 투영 됨) 해당 sourceanchor 값을 변경할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="df784-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="df784-110">지정 된 온-프레미스 AD 개체에 대해 sourceanchor 값을 지정 하려면 Azure AD Connect로 가져오기 전에 해당 msds-alloweddnssuffixesexadnomk 특성을 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="df784-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="df784-111">원본 앵커 및 ConsistencyGuid에 대 한 자세한 내용은 [Azure AD Connect: 디자인 개념](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts) 을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="df784-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

