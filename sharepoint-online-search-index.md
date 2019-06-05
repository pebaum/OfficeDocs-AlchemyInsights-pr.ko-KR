---
title: SharePoint Online에서 검색 사전 관리
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 4b51c6d44940c1a65ecf93a149430f05882452ba
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715357"
---
# <a name="search-in-sharepoint-online"></a>SharePoint Online의 검색

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin; color: black; background: white;">사용자가 SharePoint Online에서 검색 내용을 찾을 수 있도록 콘텐츠를 크롤링한 후 검색 인덱스에 추가 해야 합니다. 콘텐츠는 미리 정의 된 크롤링 일정 (크롤링 일정을 변경할 수 없음)에 따라 자동으로 크롤링됩니다. 크롤러가 마지막 크롤링 이후 변경 된 콘텐츠를 선택 하 고 인덱스를 업데이트 합니다.</span> 콘텐츠가 크롤링되 고 인덱스가 업데이트 되도록 하려면 아래 단계를 수행 합니다.</p> <ol style="margin-top: 0in;" start="1" type="1"> <li style="color: black; ; font-size: 11pt; font-style: normal; font-weight: 400; margin-left: 0in;"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin; background: white;">사이트 콘텐츠를 검색 가능 하도록 설정 하 여 콘텐츠를 찾을 수 있는지 확인 합니다. 자세한 내용은 <a href="https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable">사이트에서 콘텐츠를 검색할 수 있도록 설정</a>를 참조 하세요. <br /><br /></span></li> <li style="color: black; ; font-size: 11pt; font-style: normal; font-weight: 400; margin-left: 0in;"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin; background: white;"><span style="display: inline !important; float: none; background-color: #ffffff; color: #000000; font-family: Segoe UI,SegoeUI,Segoe WP,Helvetica Neue,Helvetica,Tahoma,Arial,sans-serif; font-size: 16px; font-style: normal; font-variant: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-decoration: none; text-indent: 0px; text-transform: none; -webkit-text-stroke-width: 0px; white-space: normal; word-spacing: 0px;">관리 속성을 변경 하거나 크롤링 속성과 관리 속성의 매핑을 변경한 후에는 변경 내용을 검색 인덱스에 반영 하기 전에 <strong>사이트를 다시 크롤링되 야</strong> 합니다. <span style="display: inline !important; float: none; background-color: #ffffff; color: #000000; font-family: Segoe UI,SegoeUI,Segoe WP,Helvetica Neue,Helvetica,Tahoma,Arial,sans-serif; font-size: 16px; font-style: normal; font-variant: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-decoration: none; text-indent: 0px; text-transform: none; -webkit-text-stroke-width: 0px; white-space: normal; word-spacing: 0px;">변경 내용이 실제 사이트가 아니라 검색 스키마에서 이루어지기 때문에 크롤러가 자동으로 사이트에 다시 인덱싱하지 않습니다.</span> </span> </span> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin; color: windowtext;">자세한 내용은 <a href="https://docs.microsoft.com/en-us/sharepoint/crawl-site-content">사이트, 라이브러리 또는 목록에 대 한 크롤링 수동 요청과 다시 인덱싱</a>를 참조 하세요.&nbsp;<br /><br /></span><strong style="mso-bidi-font-weight: normal;"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">참고:</span> </strong> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"> 크롤링을 수동으로 요청한 후 24 시간 이상 기다렸다가 전체 다시 인덱스를 대기 하 여 여전히 문제가 발생 하 고 있는지 확인 합니다. <span style="color: black; background: white;">크롤링을 시작한 후에 24 시간 이상이 통과 한 경우에는 지원 사례를 기록 하세요. 대부분의 경우에는 이미 솔루션을 사용 하 고 있습니다. 솔루션을 완료 하려면 최소한 24 시간 이상 기다려 주세요.<br /><br /></span></span><strong style="mso-bidi-font-weight: normal;"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">중요:</span></strong> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">사이트, 문서 (라이브러리) 또는 목록이 삭제 되어 여전히 검색 결과에 표시 되는 경우 사용자에 게 액세스 하려고 할 때 오류 404 파일을 찾을 수 없습니다. 라는 오류가 표시 됩니다. 이 문제는 추가 조사를 위한 지원 사례로 기록해 야 합니다. </span></li> </ol>



