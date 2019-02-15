---
title: 1385-Office-365-경고-정책
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: a0a1c749a120714c33cffd9fbdad08ea2cd6d62f
ms.sourcegitcommit: 983d08cd9ffe9542db75102b5b5c036d38eff67b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/14/2019
ms.locfileid: "30056765"
---
# <a name="office-365-alert-policies"></a><span data-ttu-id="4088a-102">Office 365 경고 정책</span><span class="sxs-lookup"><span data-stu-id="4088a-102">Office 365 Alert policies</span></span>

<span data-ttu-id="4088a-p101">office 365 Security & 준수 센터는 office 365 Enterprise 또는 office 365 US 정부 G3 또는 E5/G5 구독을 사용 하는 조직에 대 한 경고를 트리거하는 [기본 경고 정책을](https://docs.microsoft.com/office365/securitycompliance/alert-policies#default-alert-policies) 제공 합니다. 따라서 관리자는 Office365Alerts@microsoft.com에서 보낸 경고 전자 메일 알림을 "낮은 심각도 경고:*경고 정책 이름*"과 같은 제목 줄과 함께 받을 수 있습니다. 다음과 같은 일반적인 작업에 대 한 경고가 트리거되면 경고 알림이 전송 됩니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-p101">The Office 365 Security & Compliance Center offers [default alert policies](https://docs.microsoft.com/office365/securitycompliance/alert-policies#default-alert-policies) that trigger alerts for organizations with an Office 365 Enterprise or Office 365 US Government E1/G1, E3/G3, or E5/G5 subscription. Therefore, admins may receive an alert email notification sent by Office365Alerts@microsoft.com with a subject line such as "A low-severity alert:*name of alert policy*". Alert notifications are sent when alerts are triggered for common activities, such as when users:</span></span>

- <span data-ttu-id="4088a-106">전자 메일을 전달 하는 받은 편지함 규칙을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-106">Create inbox rules that forward email.</span></span>
- <span data-ttu-id="4088a-107">사용 권한을 사서함에 할당 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-107">Assign permissions their mailbox.</span></span>
- <span data-ttu-id="4088a-108">SharePoint 파일 공유에서 많은 수의 파일 공유 또는 삭제</span><span class="sxs-lookup"><span data-stu-id="4088a-108">Sharing or deleting a large number of files in SharePoint file sharing.</span></span>
- <span data-ttu-id="4088a-109">eDiscovery 검색을 만들고 검색 결과를 내보냅니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-109">Create eDiscovery searches and export search results.</span></span>
 
<span data-ttu-id="4088a-110">경고를 검토 하 고 작업을 수행 하려면</span><span class="sxs-lookup"><span data-stu-id="4088a-110">To review and act on an alert:</span></span>

1. <span data-ttu-id="4088a-111">[Security & 준수 센터로](https://protection.office.com) 이동 하 여 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-111">Go to the [Security & Compliance Center](https://protection.office.com) and sign in.</span></span>
2. <span data-ttu-id="4088a-112">**경고 > 경고 보기**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-112">Click **Alerts > View alerts**.</span></span>
3. <span data-ttu-id="4088a-113">알림을 클릭 하 여 경고에 대 한 정보가 포함 된 플라이 아웃 페이지를 표시 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-113">Click an alert to display a flyout page with information about the alert.</span></span>

<span data-ttu-id="4088a-p102">[의심 스러운 받은 편지함 규칙을 제거](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account)하는 등 경고에 대해 작업을 수행할 수 있습니다. 또는 알림 플라이 아웃 페이지에서 **해결** 을 클릭 하 여 알림을 닫아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-p102">You can take action on an alert, such as [removing a suspicious inbox rule](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account). Or you can simply close the alert by clicking **Resolve** on the alert flyout page.</span></span>

<span data-ttu-id="4088a-116">경고 정책을 구성 및 관리 하는 방법에 대 한 자세한 내용은 [이 문서](https://docs.microsoft.com/office365/securitycompliance/alert-policies)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4088a-116">For more information about configuring and managing alert policies, see  [this article](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span></span>

<span data-ttu-id="4088a-117">**중요**: Microsoft의 알림 전자 메일 알림에는 다음 작업을 수행 하 라는 메시지가 표시 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-117">**Important**: Alert email notifications from Microsoft will never ask you to do the following:</span></span>

- <span data-ttu-id="4088a-118">암호를 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-118">Provide a password.</span></span>
- <span data-ttu-id="4088a-119">계정의 보안 정보를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-119">Verify the security details of your account.</span></span>
- <span data-ttu-id="4088a-120">자신을 다시 인증 합니다.</span><span class="sxs-lookup"><span data-stu-id="4088a-120">Re-authenticate yourself.</span></span>

<span data-ttu-id="4088a-p103">이와 같은 전자 메일 메시지를 수신 하는 경우 Microsoft에서 보내지 않은 것 이며 피싱 사기로 간주 해야 합니다. 이 경우 [Microsoft에 보고](https://docs.microsoft.com/office365/SecurityCompliance/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)하세요.</span><span class="sxs-lookup"><span data-stu-id="4088a-p103">If you receive an email message like this, it was not sent by Microsoft and should be considered a phishing scam. If that happens, please [report it to Microsoft](https://docs.microsoft.com/office365/SecurityCompliance/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop).</span></span>