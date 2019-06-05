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
ms.openlocfilehash: ee154a60d80472639371d44faef464eea8734dc9
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716652"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Sharepoint/OneDrive 관리 센터에서 액세스 거부 메시지 문제 해결

<p><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Sharepoint/OneDrive 관리 센터를 탐색 하려고 할 때 액세스 거부 메시지가 표시 되는 경우 <a href="https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One">사용자에 게 라이선스를 할당 </a>했는지 확인 하세요. 사용자에 게 라이선스가 있는 경우 관리 센터에 액세스할 수 있는 <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/about-admin-roles?view=o365-worldwide">관리자 역할이 할당</a> 되었는지도 확인 해야 합니다.</span></p>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">동일한 UPN (사용자 계정 이름)을 사용 하 여 삭제 하 고 다시 만든 경우에도이 문제가 발생할 수 있습니다. 새 계정은 다른 PUID (Passport 고유 ID) 값을 사용 하 여 만들어집니다. 사용자가 사이트 모음 또는 OneDrive에 액세스 하려고 하면 사용자에 게 잘못 된 PUID가 있습니다. 두 번째 시나리오에는 Active Directory OU (조직 구성 단위)와의 디렉터리 동기화가 포함 됩니다. 사용자가 이미 SharePoint에 로그인 한 후 다른 OU로 이동 하 고 SharePoint를 사용 하 여 resynced이 문제가 발생할 수 있습니다.</span></span></p>  <ul style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" type="disc">  <li style="line-height: normal; ; font-size: 11pt; font-style: normal; font-weight: 400;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">이 문제를 해결 하려면 <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">Office 365에서 사용자 복원</a>문서의 단계와 함께 원래 UPN을 복원 해야 합니다.</span></span></li>  </ul>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><strong><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;">참고:</span></span></strong><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';"><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><em><span style="font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;font-style: normal; mso-bidi-font-style: italic;">&nbsp; 이전에 액세스 한 여러 사용자가 OneDrive 또는 SharePoint 관리 센터를 사용할 수 없는 경우 일시적인 서비스 문제가 있을 수 있습니다.</span></span></em> <em style="mso-bidi-font-style: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp;</span></em> <em><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;"> <a href="https://portal.office.com/adminportal/home#/servicehealth" target="_blank" rel="noopener"><span style="font-style: normal; mso-bidi-font-style: italic;">서비스 상태 대시보드를 확인</span></a>합니다.</span></em></span></span></p>


