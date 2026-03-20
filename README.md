# Credit Card Fraud Detection (DACON)

비지도 이상 탐지 모델을 활용한 신용카드 사기 거래 탐지 프로젝트
다음을 참고하십히오
 https://dacon.io/competitions/official/235930/overview/description

## Overview
- Unsupervised Anomaly Detection
- Label 없는 데이터에서 이상 거래 탐지

## Data
- Train/Test: 라벨 없음
- Validation: 정상/사기 라벨 포함
- 대부분 정상 + 극소수 이상치 :contentReference[oaicite:0]{index=0}

## Method
- Isolation Forest
- One-Class SVM
- Elliptic Envelope

## Key Idea
- 정상 패턴을 학습 → 벗어나면 이상치로 판단

## From this Project
- 비지도학습과 관련된 모델에 알게 되었습니다.
- 실제 데이터를 통해 비지도학습 모델을 실습해보는 경험을 얻을 수 있었습니다.
