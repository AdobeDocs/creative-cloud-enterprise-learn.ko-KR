---
title: 템플릿 라이브러리
description: 직접 프로젝트를 열고 조정할 수 있는 준비된 Firefly 그래프 템플릿을 찾아보세요
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: af06d76d4cad7ccf7adeb845d71525480b68ea4f
workflow-type: tm+mt
source-wordcount: '878'
ht-degree: 0%

---

# &#x200B;5. 템플릿 라이브러리

Firefly 그래프 템플릿의 빠른 참조 인덱스로, 각 템플릿의 제작 또는 작업에 따라 구성됩니다. 모든 예는 시작점입니다. 프로덕션 환경에서 템플릿을 사용하기 전에 자체 브랜드, 제품 및 프롬프트를 바꿉니다.

## 이미지 생성 및 스타일

* [**시작하기 - 이미지 생성**](/help/firefly/graph/templates/get-started-gen-image.md) - 이 템플릿은 기본 그래프입니다. 하나의 프롬프트 노드를 하나의 생성 노드로 하나의 출력으로 만듭니다. 이 템플릿을 첫 번째 템플릿으로 사용하여 완전히 새로운 사용자와 함께 엽니다.
* [**일관된 문자 생성**](/help/firefly/graph/templates/character-gen.md) - 이 그래프 템플릿에서 캐릭터의 참조 이미지를 로드한 다음 각각의 새 샷에 대해 장면 또는 포즈 프롬프트를 바꿉니다. 주변 장면이 변경되는 동안 문자 참조가 잠긴 상태로 유지됩니다.
* [**스타일 추출**](/help/firefly/graph/templates/style-extraction.md) — 이 그래프 템플릿에서 참조 이미지를 사용하여 색상, 빛 및 텍스처 처리를 추출할 수 있습니다. 그런 다음 동일한 그래프를 통해 실행한 새 이미지에 이 처리를 적용할 수 있습니다.
* [**일몰 분위기**](/help/firefly/graph/templates/sunset-vibes.md) - 이 그래프 템플릿에서는 텍스트 프롬프트에서 3D 타이포그래피 이미지를 만들 수 있습니다. 템플릿은 배치와 색상 균형을 자동으로 처리합니다.

## 분할 및 합성

* [**시작 - 이미지 세그먼트**](/help/firefly/graph/templates/get-started-segment-image.md) — 이 그래프 템플릿에서 소스 이미지를 로드하고 세그먼트 노드를 실행하여 피사체를 배경에서 분리합니다. 깔끔한 컷아웃을 위해 배경 교체 노드와 페어링합니다.
* [**레이어 합성 및 혼합**](/help/firefly/graph/templates/composite-blend-layers.md) — 이 그래프 템플릿에서 제품 컷아웃과 배경 장면을 별도의 레이어 입력으로 스택할 수 있습니다. 합성 이미지가 한 샷으로 읽혀질 때까지 혼합 모드와 조명 노드를 조정합니다.
* [**선택 색상 교정**](/help/firefly/graph/templates/selective-color-correction.md) — 이 그래프 템플릿에서 교정이 필요한 특정 영역을 마스킹하고 해당 노드에서만 대상 색상을 설정합니다. 이미지의 나머지 부분은 그대로 그래프를 통과합니다.

## 비디오 및 모션

* [**시작 - 비디오 생성**](/help/firefly/graph/templates/get-started-video-gen.md) - 이 그래프 템플릿에서 승인된 스틸 키 아트와 짧은 모션 프롬프트를 제공합니다. 템플릿은 새 촬영이 아닌 동일한 주요 아트로 빌드된 비디오 컷을 생성합니다.
* [**글머리 기호 시간 VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) — 이 그래프 템플릿에서는 히어로 제품 또는 피사체 이미지를 제공하여 주위에 회전하는 각도 시퀀스를 생성한 다음 고정 프레임 스윕을 자동으로 스티치합니다.

## 스토리보드 작성

* [**텍스트를 스토리보드로**](/help/firefly/graph/templates/text-to-storyboard.md) — 이 그래프 템플릿에서 텍스트 입력 노드를 스토리의 요소로 바꿀 수 있습니다. 각 줄은 고유한 스토리보드 프레임이 되며 순서대로 생성되고 단일 패널 세트로 검토를 위해 레이아웃됩니다.
* [**스토리보드 빌더**](/help/firefly/graph/templates/storyboard-builder.md) — 이 그래프 템플릿에서 장면으로 스토리보드 장면을 만들고, 서사의 비트당 하나의 노드를 추가합니다. 최종 패널 순서를 잠그기 전에 다른 시퀀스를 테스트하기 위해 노드 순서를 변경합니다.

## 3D 및 문자

* [**실시간 셰이더**](/help/firefly/graph/templates/real-time-shaders.md) — 이 그래프 템플릿에서 이미지로 시작하여 세 개의 다른 사용자 지정 셰이더를 적용하고 실시간으로 결과를 미리 볼 수 있습니다. 처음부터 다시 렌더링하지 않고 노드에서 직접 셰이더 매개 변수를 조정합니다.
* [**문자 모델 생성**](/help/firefly/graph/templates/character-model-generation.md) - 이 그래프 템플릿에서 일러스트레이션의 3D 애니메이션 스타일을 만듭니다. 템플릿은 빈 장면에서 시작하지 않고 정리를 위해 모델러에게 전달할 기본 3D 모델 패스를 생성합니다.
* [**비닐 장난감 디자인**](/help/firefly/graph/templates/vinyl-toy-design.md) — 이 그래프 템플릿에서 캐릭터 또는 마스코트 참조를 입력하고 세련된 비닐 장난감 형태로 렌더링합니다. 라이선싱 또는 제품 검토 데크에 대한 반환 각도가 있습니다.
* [**3D 턴어라운드로 스케치**](/help/firefly/graph/templates/sketch-to-3d.md) — 이 그래프 템플릿에서 스케치를 3D 문자로 변환합니다. 이 그래프는 실제 프로토타입 전에 내부 디자인을 검토할 수 있도록 3D 턴어라운드를 회전시킵니다.

## 제품 및 브랜드 목업

* [**브랜딩 시각화**](/help/firefly/graph/templates/branding-visualization.md) - 이 그래프 템플릿에서 제품 장면에 로고나 브랜드를 시각화하는 방법을 알아봅니다. 브랜드 가이드라인이나 로고 및 색상 팔레트로 피드 및 그래프를 사용하면 한 번의 실행으로 정적 키 아트와 짧은 모션 패스가 모두 출력되므로 두 포맷 모두 시각적으로 정렬된 상태를 유지할 수 있습니다.
* [**브랜드 제품 목업**](/help/firefly/graph/templates/brand-product-mockup.md) — 이 그래프 템플릿에서 다양한 장면에서 제품을 시각화하는 방법을 알아봅니다. 제품 렌더링 또는 사진을 목업 노드에 놓으면 그래프가 완전히 브랜딩된 장면 내에 배치하고 해당 장면에 자동으로 조명과 그림자를 일치시킵니다.
* [**에디토리얼 사진 촬영**](/help/firefly/graph/templates/editorial-photoshoot.md) — 이 그래프 템플릿에서 모델 참조를 로드하고 각각의 새 모양에 대한 의류 입력을 바꿉니다. 포즈 및 조명 노드는 일관된 편집 느낌을 위해 세트 전체에서 잠겨 있습니다.
* [**포토그래피 스튜디오**](/help/firefly/graph/templates/photography-studio.md) — 이 그래프 템플릿에서 스튜디오 배경에 제품 렌더링을 배치하고 결과가 실제 스튜디오 캡처처럼 읽힐 때까지 조명을 조정합니다.
* [**표면에 데칼 적용**](/help/firefly/graph/templates/decal-to-surfaces.md) - 이 그래프 템플릿에서 기본 제품 목업과 데칼 또는 로고 에셋을 별도의 입력으로 로드합니다. 이 템플릿은 컨투어를 올바르게 따르도록 데칼을 서피스 형상에 감싸줍니다.

## 일괄 처리 및 일관성 작업

* [**디자인 시스템 생성기**](/help/firefly/graph/templates/design-system-generator.md) - 이 그래프 템플릿에서 웹 사이트 스크린샷을 기반으로 디자인 시스템을 생성합니다. 그래프는 단일 배치 실행에서 일치하는 아이콘, 패턴 및 레이아웃 구성 요소 세트를 생성합니다.
* [**헤드샷 생성**](/help/firefly/graph/templates/headshots-generation.md) - 이 그래프 템플릿에서 여러 회사 헤드샷을 조화롭게 구성할 수 있습니다. 소스 사진을 한 사람당 하나씩 로드하면 그래프가 조명, 배경 및 자르기를 한 번에 전체 세트에 걸쳐 정규화합니다.

[Firefly 그래프 시작하기](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)&#x200B;(으)로 돌아갑니다.