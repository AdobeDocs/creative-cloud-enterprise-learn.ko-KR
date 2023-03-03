---
title: 기업 및 Acrobat 시리얼 번호 만료에 대한 Creative Cloud 이해
description: 기업 및 Acrobat용 Creative Cloud에 대한 시리얼 번호 만료 환경 이해
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 524d071b6f4e059823601381f04c337aedc55970
workflow-type: tm+mt
source-wordcount: '844'
ht-degree: 3%

---

# 기업 및 Acrobat 시리얼 번호 만료에 대한 Creative Cloud 이해

이전에는 Adobe이 ETLA(Enterprise Term License Agreement)(ETLA)을 통해 고객에게 앱과 함께 시리얼 번호(예: Creative Suite, 기업용 Creative Cloud, Acrobat XI, Acrobat DC)을 발급했습니다. 이러한 일련 번호에는 만료 날짜가 있습니다. 만료일이 경과하면 제품이 더 이상 작동하지 않으므로 일련 번호가 만료되기 전에 마이그레이션을 계획하는 것이 중요합니다. 이 페이지에서는 최종 사용자가 자신의 Adobe 앱 및 서비스에 계속 액세스할 수 있도록 하기 위해 필요한 단계에 대해 간략히 설명합니다.

## 일련 번호의 만료 날짜 확인

### 일련 번호 찾기

ETLA 계약과 연계된 시리얼 번호 라이선스는 [Adobe 라이선싱 웹 사이트](https://licensing.adobe.com/) (LWS). 다음 지침에 따라 표시하고 다운로드하십시오.

1. 로그인 [Adobe 라이선싱 웹 사이트](https://licensing.adobe.com/) (LWS)를 사용할 수 있습니다.
1. 선택 **라이선스 > 시리얼 번호 검색**.
1. 다음을 입력합니다. **최종 사용자 ID** 또는 **배포 대상 ID**.
1. (선택 사항) **제품 이름**, **제품 버전**, 또는 **플랫폼** 를 눌러 결과를 필터링합니다.
1. 검색을 클릭합니다.
1. 제품 이름 및 시리얼 번호가 표시됩니다.
1. (선택 사항) 일련 번호 목록을 다운로드하려면 &quot;CSV로 내보내기&quot;를 선택합니다.

![일련 번호 찾기](assets/retrieveserialnumbers.png)

### 만료일 확인

추가 [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) IT 관리자가 컴퓨터의 Adobe 제품이 만료되었거나 만료될 시리얼 번호를 사용하고 있는지 확인할 수 있는 명령줄 유틸리티입니다. 툴에는 제품 라이선싱 식별자(LEID), 암호화된 시리얼 번호 및 만료 날짜와 같은 정보가 표시됩니다. 이 [페이지](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 에는 Mac 또는 Windows 컴퓨터에서 도구를 다운로드하고 사용하는 방법에 대한 지침이 포함되어 있습니다.

## 시리얼 번호 만료 전후의 최종 사용자 경험 이해

Acrobat 및 기업용 Creative Cloud 앱 모두 만료 60일 전부터 앱에 메시지를 표시하기 시작합니다. 일련 번호가 만료되면 제품의 작동이 중지되고 사용자에게 조치를 취하라는 메시지가 표시됩니다.

### 엔터프라이즈 환경을 위한 Creative Cloud

다음은 최종 사용자 경험에 대한 간략한 설명입니다. 아래에 간단한 비디오가 있고 최종 사용자 경험을 검토합니다.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**만료 전**

시리얼 번호가 만료되기 60일 전부터 모든 엔터프라이즈 앱용 Creative Cloud은 제품 내 대화 상자를 최종 사용자에게 표시합니다. 이 메시지는 만료 30일 전까지 매주 표시되며 만료 날짜까지 매일 표시됩니다. *라이선스 만료 예정 이 Adobe 제품은 2020년 11월 29일에 만료되는 라이선스를 사용하고 있습니다. 계속 액세스하려면 관리자에게 문의하세요.*.

![만료 전 CCE 메시지](assets/cceexpiring.png)

**만료 후**

시리얼 번호가 만료되면 사용자는 더 이상 기업용 앱의 Creative Cloud에 액세스할 수 없습니다. 만료 후 첫 번째 실행 시 다음과 같은 대화 상자가 표시됩니다. *입력한 시리얼 번호가 만료되었습니다. 이 제품에 라이선스를 부여할 수 없습니다. 고객 지원에 문의하십시오.*.

![만료 후 CCE 메시지](assets/cceafterexpire.png)

이후의 모든 앱 실행 시도에 대해 최종 사용자에게 **지금 로그인** 자체 Adobe ID을 만들고 체험판 모드로 전환하는 옵션이 표시됩니다. 단, 최종 사용자가 생성한 모든 새로운 Adobe ID은 조직의 라이선스와 연결되지 않으며 사용자에게 추가적인 혼동을 줄 것입니다. 업무 중단 및/또는 불필요한 혼란을 방지하려면 일련 번호가 만료되기 전에 사용자를 지정된 사용자 라이선싱으로 마이그레이션하십시오.

![CCE 로그인 대화 상자 1](assets/ccesignin1.png)

![CCE 로그인 대화 상자 2](assets/ccesignin2.png)

### Acrobat 환경

다음은 최종 사용자 경험에 대한 간략한 설명입니다. 아래에 간단한 비디오가 있고 최종 사용자 경험을 검토합니다.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**만료 전**

일련 번호가 만료되기 60일 전부터 Acrobat은 최종 사용자에게 제품 내 팝업 메시지를 표시합니다. 이는 만료 7일 전까지 주 1회 표시됩니다. 그러면 매일 다음과 같이 나타나기 시작합니다 *Adobe Acrobat 라이선스는 2020년 30월 11일에 만료됩니다. Acrobat을 중단 없이 계속 사용하려면 관리자에게 문의하십시오.*

![Acrobat 만료 메시지](assets/acrobatexpiring.png)

**만료 후**

시리얼 번호가 만료되면 사용자는 더 이상 Acrobat에 액세스할 수 없습니다. 만료 후 첫 번째 실행 시 다음과 같은 대화 상자가 표시됩니다. *입력한 시리얼 번호가 만료되었습니다. 이 제품에 라이선스를 부여할 수 없습니다. 고객 지원에 문의하십시오.*

![만료 후 Acrobat 메시지](assets/acrobatafterexpire.png)

이후 Acrobat을 실행하려는 모든 시도에 대해 최종 사용자에게 **지금 로그인** 자체 Adobe ID을 만들고 체험판 모드로 전환하는 옵션이 표시됩니다. 단, 최종 사용자가 생성한 모든 새로운 Adobe ID은 조직의 라이선스와 연결되지 않으며 사용자에게 추가적인 혼동을 줄 것입니다.

![대화 1의 Acrobat Sign](assets/acrobatsignin1.png)

![대화 2의 Acrobat Sign](assets/acrobatsignin2.png)

## 도움이 필요한 경우 문의

PDF 파일의 [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) 툴이나 시리얼 번호 배포에서 지정된 사용자로 마이그레이션하는 데 도움이 필요한 경우 다음과 같은 몇 가지 옵션이 있습니다.
* Adobe 기업 온보딩 팀에 이메일 보내기 - **entonb@adobe.com**
* 에서 지원 티켓 열기 [Admin Console](https://adminconsole.adobe.com/support)
* Adobe 계정 팀에 문의하십시오.
