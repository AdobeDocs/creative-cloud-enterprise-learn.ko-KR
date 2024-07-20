---
title: 기업 및 Acrobat 시리얼 번호 만료에 대한 Creative Cloud 이해
description: 기업 및 Acrobat용 Creative Cloud에 대한 시리얼 번호 만료 경험 이해
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '840'
ht-degree: 1%

---

# 기업 및 Acrobat 시리얼 번호 만료에 대한 Creative Cloud 이해

이전에는 Adobe이 앱(예: Creative Suite, 기업용 Creative Cloud, Acrobat XI, Acrobat DC)과 함께 Enterprise Term License Agreements(ETLA)를 사용하는 고객에게 발급한 시리얼 번호입니다. 이러한 시리얼 번호는 만료 날짜가 있습니다. 만료 날짜가 지나면 제품은 더 이상 작동하지 않으므로 시리얼 번호가 만료되기 전에 마이그레이션을 계획하는 것이 중요합니다. 이 페이지에서는 최종 사용자가 Adobe 앱 및 서비스에 계속 액세스할 수 있도록 하는 데 필요한 단계를 설명합니다.

## 시리얼 번호의 만료 날짜 확인

### 시리얼 번호 찾기

ETLA 계약과 관련된 시리얼 번호 라이선스는 [Adobe 라이선싱 웹 사이트](https://licensing.adobe.com/)(LWS)를 통해 사용할 수 있습니다. 표시 및 다운로드하려면 다음 지침을 따르십시오.

1. Adobe ID과 암호를 사용하여 [Adobe 라이선싱 웹 사이트](https://licensing.adobe.com/)(LWS)에 로그인합니다.
1. **라이선스 > 시리얼 번호 검색**&#x200B;을 선택합니다.
1. **최종 사용자 ID** 또는 **배포 대상 ID**&#x200B;를 입력하세요.
1. (선택 사항) **제품 이름**, **제품 버전** 또는 **플랫폼**&#x200B;을 선택하여 결과를 필터링합니다.
1. [검색]을 클릭합니다.
1. 제품 이름 및 시리얼 번호가 표시됩니다.
1. (선택 사항) &quot;CSV로 내보내기&quot;를 선택하여 일련 번호 목록을 다운로드합니다.

![시리얼 번호 찾기](assets/retrieveserialnumbers.png)

### 만료일 확인

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)은 IT 관리자가 컴퓨터의 Adobe 제품에서 만료되거나 만료될 시리얼 번호를 사용하고 있는지 확인할 수 있는 명령줄 유틸리티입니다. 이 도구는 제품 라이선싱 식별자(LEID), 암호화된 시리얼 번호 및 만료 날짜와 같은 정보를 표시합니다. 이 [페이지](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)에는 Mac 또는 Windows 컴퓨터에서 도구를 다운로드하고 사용하는 방법에 대한 지침이 포함되어 있습니다.

## 시리얼 번호 만료 전후의 최종 사용자 경험 이해

Acrobat 및 기업용 Creative Cloud 앱 모두 만료 60일 전부터 앱에 메시지가 표시되기 시작합니다. 시리얼 번호가 만료되면 제품의 작동이 중단되고 사용자에게 조치를 취하라는 메시지가 표시됩니다.

### 기업 환경을 위한 Creative Cloud

다음 정보는 최종 사용자 경험에 대한 간략한 설명입니다. 아래에 짧은 비디오가 있고 그 뒤에 최종 사용자 경험을 검토합니다.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**만료 전**

시리얼 번호가 만료되기 60일 전부터 기업 앱의 모든 Creative Cloud은 최종 사용자에게 제품 내 대화 상자를 표시합니다. 이 메시지는 매주 만료 30일 전까지 표시되며, 만료 날짜까지 매일 *라이선스가 만료됩니다. 이 Adobe 제품은 2020년 11월 29일에 만료되는 라이선스를 사용하고 있습니다.*&#x200B;에 계속 액세스하려면 관리자에게 문의하십시오.

![만료 전 CCE](assets/cceexpiring.png)

**만료 후**

시리얼 번호가 만료되면 사용자는 더 이상 기업용 앱의 Creative Cloud에 액세스할 수 없습니다. 만료 후 첫 번째 실행 시 사용자에게 *입력한 시리얼 번호가 만료되었습니다.라는 대화 상자가 표시됩니다. 이 제품에는 라이선스를 부여할 수 없습니다. 고객 지원 센터*&#x200B;에 문의하십시오.

![만료 후 CCE](assets/cceafterexpire.png)

이후에 앱을 실행하려는 모든 시도에 대해 최종 사용자에게 **지금 로그인**&#x200B;하라는 메시지가 표시되고 그 다음에 자체 Adobe ID을 만들고 체험판 모드를 시작하는 옵션이 표시됩니다. 그러나 최종 사용자가 생성한 모든 새 Adobe ID은 조직의 라이선스와 연결되지 않으며 사용자에게 추가적인 혼란을 야기합니다. 비즈니스 중단 및/또는 불필요한 혼란을 방지하려면 시리얼 번호가 만료되기 전에 사용자를 지정된 사용자 라이선싱으로 마이그레이션하십시오.

![CCE 로그인 대화 상자 1](assets/ccesignin1.png)

![CCE 로그인 대화 상자 2](assets/ccesignin2.png)

### Acrobat experience

다음 정보는 최종 사용자 경험에 대한 간략한 설명입니다. 아래에 짧은 비디오가 있고 그 뒤에 최종 사용자 경험을 검토합니다.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**만료 전**

일련 번호가 만료되기 60일 전부터 Acrobat은 최종 사용자에게 제품 내 팝업 메시지를 표시합니다. 이는 만료 7일 전까지 일주일에 한 번 나타납니다. 그러면 매일 *Adobe Acrobat 라이선스가 2020년 30월 11일에 만료됩니다. Acrobat을 중단 없이 계속 사용하려면 관리자에게 문의하십시오.*

![Acrobat 만료 메시지](assets/acrobatexpiring.png)

**만료 후**

시리얼 번호가 만료되면 사용자는 더 이상 Acrobat에 액세스할 수 없습니다. 만료 후 첫 번째 실행 시 사용자에게 *입력한 시리얼 번호가 만료되었습니다.라는 대화 상자가 표시됩니다. 이 제품에는 라이선스를 부여할 수 없습니다. 고객 지원에 문의하세요.*

![만료 후 Acrobat](assets/acrobatafterexpire.png)

이후에 Acrobat을 시작하려고 하면 최종 사용자에게 **지금 로그인**&#x200B;하라는 메시지가 표시되고 그 다음에 자체 Adobe ID을 만들고 체험판 모드를 시작하는 옵션이 표시됩니다. 그러나 최종 사용자가 생성한 모든 새 Adobe ID은 조직의 라이선스와 연결되지 않으며 사용자에게 추가적인 혼란을 야기합니다.

![대화 상자 1](assets/acrobatsignin1.png)의 Acrobat Sign

![대화 상자 2](assets/acrobatsignin2.png)의 Acrobat Sign

## 도움이 필요한 경우 당사에 문의

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 도구 사용에 대한 질문이 있거나 시리얼 번호 배포에서 지정된 사용자로 마이그레이션하는 데 도움이 필요한 경우, 다음과 같은 몇 가지 옵션을 사용할 수 있습니다.
* Adobe Enterprise 온보딩 팀으로 전자 메일 보내기 - **entonb@adobe.com**
* [Admin Console](https://adminconsole.adobe.com/support)에서 지원 티켓 열기
* Adobe 계정 팀에 문의
