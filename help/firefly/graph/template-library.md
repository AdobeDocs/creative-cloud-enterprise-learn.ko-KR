---
title: 템플릿 라이브러리
description: 직접 프로젝트를 열고 조정할 수 있는 준비된 Firefly 그래프 템플릿을 찾아보세요
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-22134
hide: true
hidefromtoc: true
source-git-commit: bd878f1297ab60bcdf5e9e7e2d8c5ab9fa6a68b5
workflow-type: tm+mt
source-wordcount: '609'
ht-degree: 3%

---

# &#x200B;5. 템플릿 라이브러리

Firefly 그래프 템플릿의 빠른 참조 인덱스로, 각 템플릿의 제작 또는 작업에 따라 구성됩니다. 모든 예는 시작점입니다. 프로덕션 환경에서 템플릿을 사용하기 전에 자체 브랜드, 제품 및 프롬프트를 바꿉니다.

## 이미지 생성 및 스타일

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**시작 - 이미지 생성**](/help/firefly/graph/templates/get-started-gen-image.md) | 하나의 프롬프트 노드를 하나의 생성 노드로 하나의 출력으로 변환하는 기본 그래프. | <ul><li>히어로 이미지</li><li>Placeholder test</li><li>샘플 이미지</li></ul> |
| [**일관된 문자 생성**](/help/firefly/graph/templates/character-gen.md) | 캐릭터의 참조 이미지 하나를 로드한 다음 새 샷마다 장면 또는 포즈 프롬프트를 바꿉니다. | <ul><li>재발성 마스코트</li><li>스포크 문자</li><li>강사 문자</li></ul> |
| [**스타일 추출**](/help/firefly/graph/templates/style-extraction.md) | 참조 이미지를 피드하여 색상, 조명 및 텍스처 처리를 추출합니다. | <ul><li>룩 트랜스퍼</li><li>시즌별 룩 매치</li><li>무드 일치</li></ul> |
| [**일몰 분위기**](/help/firefly/graph/templates/sunset-vibes.md) | 텍스트 프롬프트에서 3D 타이포그래피 이미지를 만듭니다. | <ul><li>태그라인 오버레이</li><li>계절별 태그라인</li><li>Flash 판매 자산</li></ul> |

## 분할 및 합성

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**시작하기 - 이미지 세그먼트**](/help/firefly/graph/templates/get-started-segment-image.md) | 소스 이미지를 로드하고 분할 노드를 실행하여 배경에서 피사체를 분리합니다. | <ul><li>컷아웃 정리</li><li>카탈로그 분리</li><li>일괄 교체</li></ul> |
| [**레이어 합성 및 혼합**](/help/firefly/graph/templates/composite-blend-layers.md) | 제품 컷아웃과 배경 장면을 별도의 레이어 입력으로 쌓습니다. | <ul><li>라이프스타일/소셜 복합</li><li>홈페이지 배너</li><li>o-브랜드 합성</li></ul> |
| [**선택 색상 교정**](/help/firefly/graph/templates/selective-color-correction.md) | 수정이 필요한 특정 영역을 마스킹하고 해당 노드에서만 대상 색상을 설정합니다. | <ul><li>브랜드 색상 일치</li><li>색상 표준화</li><li>스트레이 색상 수정</li></ul> |

## 비디오 및 모션

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**시작 - 비디오 생성**](/help/firefly/graph/templates/get-started-video-gen.md) | 승인된 스틸 키 아트와 짧은 모션 프롬프트를 피드합니다. | <ul><li>주요 아트를 비디오로</li><li>Launch 티저</li><li>비디오 잘라내기</li></ul> |
| [**글머리 기호 시간 VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | 히어로 제품 또는 피사체 이미지를 공급하여 그 주위에 회전 각도 시퀀스를 생성한 다음 고정 프레임 스윕을 자동으로 스티치합니다. | <ul><li>글머리 기호 시간 샷</li><li>360 프레임 고정</li><li>회전하는 영웅 샷</li></ul> |

## 스토리보드 작성

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**스토리보드에 텍스트 추가**](/help/firefly/graph/templates/text-to-storyboard.md) | 텍스트 입력 노드를 스토리의 요소로 바꿉니다. | <ul><li>스토리보드에 스크립팅</li><li>스토리보드 실행</li><li>설명 스토리보드</li></ul> |
| [**스토리보드 빌더**](/help/firefly/graph/templates/storyboard-builder.md) | 스토리보드 장면을 장면별로 구성하여, 서사의 비트당 하나의 노드를 추가한다. | <ul><li>내러티브 구조 시험</li><li>속도 검사</li><li>내러티브 아크</li></ul> |

## 3D 및 문자

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**실시간 셰이더**](/help/firefly/graph/templates/real-time-shaders.md) | 이미지를 사용하여 시작하고 서로 다른 세 가지 사용자 정의 셰이더를 적용하여 실시간으로 결과를 미리 볼 수 있습니다. | <ul><li>구성기 셰이더</li><li>페인트 재질 미리보기</li><li>제품 렌더링</li></ul> |
| [**문자 모델 생성**](/help/firefly/graph/templates/character-model-generation.md) | 일러스트레이션의 3D 애니메이션 스타일을 만듭니다. | <ul><li>마스코트 모형</li><li>기본 3D 모델</li><li>강사 모델</li></ul> |
| [**비닐 장난감 디자인**](/help/firefly/graph/templates/vinyl-toy-design.md) | 캐릭터 또는 마스코트 참조를 입력하고 스타일화된 비닐 장난감 형식으로 렌더링합니다. | <ul><li>수집 가능한 개념</li><li>마스코트 도형</li><li>라이선싱 피치</li></ul> |
| [**3D 턴어라운드로 스케치**](/help/firefly/graph/templates/sketch-to-3d.md) | 스케치를 3D 캐릭터로 변환. | <ul><li>하드웨어 전환</li><li>차량 및 소품 교체</li><li>문자 전환</li></ul> |

## 제품 및 브랜드 목업

| 그래프 템플릿 | 설명 | 사용 사례 |
|---|---|---|
| [**브랜딩 시각화**](/help/firefly/graph/templates/branding-visualization.md) | 제품 장면에서 로고 또는 브랜드를 시각화합니다. | <ul><li>하위 브랜드 시각적 요소</li><li>팔레트 테스트</li><li>ID 미리 보기</li></ul> |
| [**브랜드 제품 목업**](/help/firefly/graph/templates/brand-product-mockup.md) | 다양한 장면에서 제품을 시각화합니다. | <ul><li>매장 내 목업</li><li>제품 목업</li><li>건축용 모형</li></ul> |
| [**에디토리얼 사진 촬영**](/help/firefly/graph/templates/editorial-photoshoot.md) | 모델 참조를 로드하고 새 모양마다 의복 입력을 바꿉니다. | <ul><li>룩북 슛</li><li>에디토리얼 시리즈</li><li>컬러웨이 라인업</li></ul> |
| [**사진 스튜디오**](/help/firefly/graph/templates/photography-studio.md) | 스튜디오 배경에 제품 렌더링을 배치하고 결과가 실제 스튜디오 캡처처럼 읽힐 때까지 조명을 조정합니다. | <ul><li>SKU 스튜디오 샷</li><li>페이지 렌더링 시작</li><li>제품 라인 샷</li></ul> |
| [**표면에 데칼 적용**](/help/firefly/graph/templates/decal-to-surfaces.md) | 기본 제품 목업과 데칼 또는 로고 에셋을 별도의 입력으로 로드합니다. | <ul><li>브랜드 변경 미리 보기</li><li> 라이버리 미리보기</li><li>로고 배치 테스트</li></ul> |

## 일괄 처리 및 일관성 작업

| 그래프 템플릿 | 설명** | 사용 사례 |
|---|---|---|
| [**디자인 시스템 생성기**](/help/firefly/graph/templates/design-system-generator.md) | 웹 사이트 스크린샷을 기반으로 디자인 시스템을 생성합니다. | <ul><li>아이콘 패턴 설정</li><li>색상 체계</li><li>시각적 언어</li></ul> |
| [**헤드샷 생성**](/help/firefly/graph/templates/headshots-generation.md) | 여러 회사 헤드샷을 조화롭게 구성하세요. | <ul><li>디렉터리 헤드샷</li><li>팀 페이지 헤드샷</li><li>프로 헤드샷</li></ul> |
