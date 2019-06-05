---
title: 액세스 거부 메시지 문제 해결
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 1b515e445caa25136960602f73bef1e21e753bc4
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715917"
---
# <a name="troubleshoot-access-denied-messages"></a>액세스 거부 메시지 문제 해결

<p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">Sharepoint Online 사이트를 찾아보는 동안 액세스 거부 메시지가 수신 되는 경우 아래 문서를 참조 하세요.&nbsp;</span></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><strong><u><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">사용자 추가 및 라이선스를 허가 합니다.</span></u></strong></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';"><a href="https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One">비즈니스용 Office 365에서 사용자에 게 라이선스를 할당</a>했는지 확인 합니다.</span></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><strong><u><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">사용 권한 할당</span></u></strong><u></u></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">사용자에 게 Sharepoint 라이선스가 할당 되 고 여전히 액세스 거부 메시지를 수신 하는 경우에는 <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">해당 권한 수준이 할당</a> 되어 있는지 확인 하세요.</span></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><strong><u><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">액세스 요청 기능 사용 고려</span></u></strong><u></u></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';"><a href="https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3">액세스 요청 기능</a> 을 사용 하면 사용자가 현재 볼 수 있는 권한이 없는 콘텐츠에 대 한 액세스를 요청할 수 있습니다.</span></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><strong><u><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">사용자 지정 스크립트를 허용 하면 액세스 거부 문제가 발생할 수 있음</span></u></strong><u></u></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">사용자 지정 스크립트 &ldquo;&rdquo; 허용 기능이 액세스 거부를 표시할 수 있는 몇 가지 시나리오가 있습니다. 영향을 받는 기능 목록, 보안 고려 사항 및 기능을 사용 하지 않도록 설정 하는 기능 <a href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">사용자 지정 스크립트를 방문 하거나 허용 하거나 금지</a>합니다.</span></p> <p style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; line-height: normal;"><strong><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">참고</span></strong><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';">:&nbsp;<em>이전에 액세스 한 여러 사용자가 OneDrive 또는 SharePoint 사이트를 사용할 수 없는 경우 일시적인 서비스 문제가 있을 수 있습니다.&nbsp; <a href="https://portal.office.com/adminportal/home#/servicehealth" target="_blank" rel="noopener">서비스 상태 대시보드를 확인</a>합니다.</em></span></p>


  

