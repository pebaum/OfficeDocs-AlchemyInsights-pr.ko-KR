---
title: DKIM 설정 문제 해결
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: d725eb0d46dcbf1b5b6d77ca9f59fcafa5298bf1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43717568"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="0a23e-102">DKIM 설정 문제 해결</span><span class="sxs-lookup"><span data-stu-id="0a23e-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="0a23e-103">사용자 지정 도메인에 대해 DKIM을 사용 하도록 설정 하는 데 문제가 발생 하면 다음 단계를 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="0a23e-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="0a23e-104">대부분의 DKIM 설정 문제는 잘못 된 DNS 레코드와 관련이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0a23e-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="0a23e-105">TXT 레코드가**아닌** DKIM CNAME 레코드의 서식이 올바르게 지정 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="0a23e-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="0a23e-106">자세한 내용은이 [항목](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="0a23e-106">For more information, see this [topic](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

- <span data-ttu-id="0a23e-107">도메인의 DNS 호스팅 서비스 (대개 도메인 등록자)에서 DKIM DNS 레코드를 만들거나 업데이트 한 후에는 DNS 레코드가 전파 될 때까지 기다립니다.</span><span class="sxs-lookup"><span data-stu-id="0a23e-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="0a23e-108">관리 센터 \<에서 DKIM DNS 레코드를 만들 수 없는 경우 customdomain\> 을 사용자 지정 도메인 (예: `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`Contoso.com)으로 바꾸고 [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell)에서이 명령을 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0a23e-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
