<img align="right" width="128" src="./assets/profile-avatar-500.png" alt="Seo Jihye AI portfolio avatar" />

# 서지혜 · Seo Jihye

**Applied AI/ML Engineer** building reliable systems for batteries, edge vision, and mobility.

현실의 물리 제약과 운영 맥락을 모델에 연결하고, 실험 결과를 재현 가능한 코드와 제품형 데모로 완성하는 데 관심이 있습니다.

_Updated through 2026-10-09_

## Recent progress

- 해양 배터리 SOC 연구를 단일 TCN 실험에서 **GRU, TCN, Tiny Transformer, CNN-Attention-LSTM** 비교 파이프라인으로 확장했습니다.
- 모델 선택용 validation-only 실험을 5개 random seed로 반복했으며, GRU가 평균 MAE **0.613%p**로 가장 낮았습니다. 이 수치는 test 결과가 아닌 모델 선택 단계의 검증 결과입니다.
- 공개 데이터의 물리 특성을 이용해 약 **271만 행**의 해양 프록시 시계열을 재생성하고, 원천 시퀀스 분리와 물리 범위·제약 조건을 점검했습니다.
- 학회 논문과 초록을 정리하면서 결과의 범위를 공개 데이터 기반 프록시 내부 검증으로 제한했습니다. 실제 선박 계측 데이터에 대한 외부 검증은 다음 단계입니다.

## Featured projects

### [Physics-Guided Marine Battery SOC](https://github.com/seojeejee/physics-guided-marine-battery-soc)

차량용 공개 배터리 데이터와 물리 기반 해양 프록시를 결합한 시계열 SOC 추정 연구입니다.

- GPU Temporal Convolutional Network와 physics-guided augmentation
- 해양 프록시 MAE **1.808%p → 1.024%p**
- 5개 random seed에서 모두 개선
- GRU·TCN·Tiny Transformer·CNN-Attention-LSTM의 5-seed validation 비교
- 데이터 누수 방지 split, constraint audit, Streamlit dashboard

`Python` `PyTorch` `GRU` `TCN` `Time Series` `Battery AI` `Scientific ML`

### [Jetson Safety-Zone Intrusion Detection](https://github.com/seojeejee/jetson-safety-zone-intrusion-detection)

YOLO11 객체 탐지와 다각형 안전구역 판정을 결합한 Jetson 엣지 AI 프로토타입입니다.

- 전체 mAP@0.5 **0.795**, mAP@0.5:0.95 **약 0.609**
- Bus AP@0.5 **0.975**, Person AP@0.5 **0.614**
- TensorRT FP16 변환 및 실시간 카메라 추론 경로
- 학습 결과, 한계, 후속 실험을 포함한 학술대회 연구 정리

`YOLO11` `TensorRT` `Jetson` `OpenCV` `Edge AI`

### [MOVE AI · 길새김](https://github.com/seojeejee/MOVE-AI)

운송자의 현장 판단을 데이터로 포착하고 관리자 검증을 거쳐 다음 운행에 재사용하는 해커톤 팀 프로젝트입니다.

- GPS 반경 필터, GeoJSON 지오펜스, 속도 이상 후보 탐지
- 시설 진입·대기·이탈 이벤트와 SQLite 저장
- 사진·음성 제보 및 관리자 승인 워크플로
- 모바일 우선 웹 UI와 Streamlit 배포 번들

`Python` `JavaScript` `GeoJSON` `SQLite` `Streamlit`

## What I work with

- **AI/ML:** PyTorch, YOLO, temporal CNN, model evaluation, physics-guided learning
- **Edge & vision:** TensorRT, Jetson, OpenCV, real-time inference
- **Data & backend:** NumPy, pandas, scikit-learn, REST API, SQLite, GeoJSON
- **Delivery:** Streamlit, reproducible experiments, technical documentation

## Engineering principles

- 결과 숫자와 함께 데이터 출처, 평가 조건, 한계를 공개합니다.
- 모델이 모르는 것과 아직 시연 단계인 기능을 명확히 구분합니다.
- 실제 사용자의 의사결정과 안전을 고려해 AI와 규칙 기반 로직의 역할을 나눕니다.
- README에서 문제 → 접근 → 검증 → 실행 방법을 빠르게 확인할 수 있게 구성합니다.

## Current focus

Marine battery SOC modeling, multi-seed model comparison, edge deployment, and trustworthy decision-support systems.
