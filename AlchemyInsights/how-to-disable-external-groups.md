---
title: 외부 그룹을 사용 하지 않도록 설정 하는 방법
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4d911c319c3e8e327f9b3af3ba67816e646bc468
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29899142"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="4ae34-102">외부 그룹을 사용 하지 않도록 설정 하는 방법</span><span class="sxs-lookup"><span data-stu-id="4ae34-102">How to disable External Groups</span></span>

<span data-ttu-id="4ae34-p101">Exchange 전송 규칙 (ETRs) 회사 정보 공유 되지 않도록 방지 하기 위해 사전 컨트롤 집합을 적용 하는 외부 메시징 yammer 합니다. 외부 그룹 만들기 (영문)에서 사용자를 제한 하기 위해 (ETR)는 Exchange 전송 규칙을 구성 하 고 다음 외부 메시징 차단 하도록 Exchange 전송 규칙을 사용 하 여 Yammer를 구성 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4ae34-p101">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared. In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span> 
  
<span data-ttu-id="4ae34-105">Exchange Online 관리 센터에서 규칙을 만든 후에 Yammer에 적용할 ETR를 설정 하려면 다음이 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="4ae34-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="4ae34-106">확인 된 관리자로 및 **Yammer 관리 센터**에서 Yammer에 로그온, C로 이동 **ontent 및 보안 \> 보안 설정.**</span><span class="sxs-lookup"><span data-stu-id="4ae34-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **ontent and Security \> Security Settings.**</span></span>
    
- <span data-ttu-id="4ae34-107">**외부 메시징**, 선택 **Yammer의 Exchange Online Exchange 전송 규칙 (ETRs)를 적용 합니다.**</span><span class="sxs-lookup"><span data-stu-id="4ae34-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>
    
- <span data-ttu-id="4ae34-108">**Save(저장)** 를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="4ae34-108">Choose **Save**.</span></span> 
    
<span data-ttu-id="4ae34-109">자세한 내용은 [Exchange 전송 규칙을 사용 하 여 Yammer 네트워크에서 메시징 외부 컨트롤](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9) 을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4ae34-109">For more information, see [Control external messaging in a Yammer network with Exchange Transport rules](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span></span>
  

