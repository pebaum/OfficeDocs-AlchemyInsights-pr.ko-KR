---
title: 감사 로그의 사서함에 대 한 외부 전자 메일 전달 확인
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 43b6a26bc05892e71d41c4b47522785245cb4851
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35383103"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="642da-102">사서함에 대해 외부 전자 메일 전달이 구성 된 시기 식별</span><span class="sxs-lookup"><span data-stu-id="642da-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="642da-103">사용자가 사서함에서 외부 전자 메일 전달을 구성 하면 해당 활동은 **설정 된 사서함** cmdlet의 일부로 감사 됩니다.</span><span class="sxs-lookup"><span data-stu-id="642da-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="642da-104">보안 & 준수 센터에서 감사 로그 검색을 사용 하 여 작업을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="642da-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="642da-105">[Office 365 보안 & 준수 센터](https://protection.office.com/) 에 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="642da-106">**검색 및 조사** 를 클릭 하 고 **감사 로그 검색**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="642da-107">**시작 날짜** 및 **끝 날짜** 필드에서 날짜 범위를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="642da-108">사용자 이름을 지정할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="642da-108">You don't need to specify a username.</span></span> <span data-ttu-id="642da-109">**모든 활동에 대 한 결과를 표시**하도록 **작업** 필드가 설정 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="642da-110">**검색**을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-110">Click **Search**.</span></span>

<span data-ttu-id="642da-111">결과에서 **결과 필터링** 을 클릭 하 고 활동 필터 상자에 **Set-Mailbox** 를 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="642da-112">결과에서 감사 레코드를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-112">Select an audit record in the results.</span></span> <span data-ttu-id="642da-113">**세부** 정보 플라이 아웃에서 **추가 정보**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="642da-114">각 감사 레코드의 세부 정보를 확인 하 여 해당 활동이 전자 메일 전달과 관련 되는지 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="642da-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="642da-115">**ObjectId**: 수정 된 사서함의 별칭 값입니다.</span><span class="sxs-lookup"><span data-stu-id="642da-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="642da-116">**Parameters**: _ForwardingSmtpAddress_ 는 대상 전자 메일 주소를 나타냅니다.</span><span class="sxs-lookup"><span data-stu-id="642da-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="642da-117">**UserId**: **ObjectId** 필드의 사서함에 대 한 전자 메일 전달을 구성한 사용자입니다.</span><span class="sxs-lookup"><span data-stu-id="642da-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="642da-118">자세한 내용은 [사서함에 대 한 전자 메일 전달을 설정한 사용자 결정](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="642da-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
