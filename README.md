# SafeAlert: AI-based Disaster Safety Information App

<img width="751" height="739" alt="Image" src="https://github.com/user-attachments/assets/46b1a070-92a7-4c28-9f60-c51e2eddd660" />

---

## Overview
재난은 언제 어디서든 발생할 수 있으며, 빠른 대처와 정확한 정보 전달이 국민의 안전을 지키는 핵심 요소입니다.  
SafeAlert는 기존 재난 안전 앱들의 한계를 보완하고, **AI 기반 예측 및 실시간 대피소 안내** 기능을 제공하는 통합 재난안전정보 앱입니다.  

이 프로젝트는 **원저자의(프로젝트 창안자) 아이디어를 바탕으로 설계 및 개발되었으며**, 해당 아이디어를 기반으로 **KAICTS (Published in Korea Artificial-Intelligence Convergence Technology Society Conference Spring 2024)** 학회에서 발표되었습니다.

---

## Motivation
현재 운영 중인 다양한 재난 안전 앱은 다음과 같은 한계가 있습니다:
- **안전디딤돌**: 실시간 상황 정보 부족, 대피소 위치 정확도 낮음  
- **전국재난문자**: 외국어 미지원, 재난 상세 정보 부족  
- **경기안전 대동여지도**: 대피소 수용인원 조회 불가  
- **서울안전누리**: 대피소 정보 부족  

SafeAlert는 이러한 문제들을 해결하기 위해 설계되었습니다.

---

## Key Features
- **실시간 대피소 안내**: 재난문자 + 현재 위치 기반 대피소 추천  
- **반려동물 대피 지원**: 반려동물과 함께 안전하게 이동할 수 있는 대피소 제공  
- **응급/장애인 대피소**: 이동 취약 계층을 위한 맞춤형 대피소 안내  
- **다국어 지원**: 외국인 거주자를 위한 다국어 인터페이스  
- **실시간 인구 밀도 & 수용 인원**: 혼잡하지 않은 대피소 추천  
- **AI 기반 분석**
  - **BERT**: 재난문자에서 위치, 시간, 유형 추출  
  - **GNN (Graph Neural Networks)**: 최적의 대피 경로 탐색  
  - **GPT**: 재난 대응 요약 및 대응 방안 제시  

---

## System Architecture
```
(재난문자 → AI 분석 → 대피소 추천의 흐름 구조)
```

<img width="1160" height="646" alt="Image" src="https://github.com/user-attachments/assets/42dc782a-a648-4034-9262-d0bccc9b22f9" />


---

## UI/UX Design
- **메인 메뉴**
  - 실시간 대피장소
  - 재난대피장소 목록
  - 반려동물 대피장소
  - 응급/장애인 대피장소
- **지도 기반 안내**: 현재 위치에서 가장 가까운 안전 대피소 제공

<img width="1019" height="569" alt="Image" src="https://github.com/user-attachments/assets/92d95621-6ced-42c5-bafe-3094f35f2e8d" />

<img width="1023" height="575" alt="Image" src="https://github.com/user-attachments/assets/d8749f00-6057-421a-97e4-aca40462ba41" />

<img width="1021" height="572" alt="Image" src="https://github.com/user-attachments/assets/6a336263-927b-4cea-b71f-973ba89b5b51" />

---

## Publication
이 아이디어는 아래 학회에서 발표되었습니다:  
- **Conference**: KAICTS (Published in Korea Artificial-Intelligence Convergence Technology Society Conference Spring 2024)
- **Year**: 2024 
- **Authors**: 임예슬, 이지현, 고훈준, 조선문  

> 원문 논문은 학회 저작권에 따라 공개하지 않고, 요약 및 프로젝트 설명만 포함합니다.  

---

## Future Work
- 정부 API 연동 (재난문자, 대피소 정보 실시간 업데이트)  
- 실제 모바일 앱 프로토타입 제작 (Android/iOS)  
- 실시간 인구밀도 수집 및 예측 기능 고도화  
- 사용자 피드백 & 커뮤니티 기능 추가  

<img width="1017" height="569" alt="Image" src="https://github.com/user-attachments/assets/5fb48b99-1847-4d3b-af04-8d6ae40a5d67" />

---

## Contributors
- 임예슬 (Project Leader, AI Model Design, App Design, Idea Contributor)  
- 이지현 (App Design)  
- 고훈준 (Research Paper Writing, Academic Publication)  
- 조선문 (Research Paper Writing, Academic Publication)  

---

## License
이 프로젝트는 연구/학술적 목적을 위한 공개 저장소입니다.  
상업적 활용 전에는 별도의 협의가 필요합니다.  
