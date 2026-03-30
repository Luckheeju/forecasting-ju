# ⚡ 전력 거래 시뮬레이션 (forecasting-ju)
전력 거래소의 수요 예측 및 전력 거래 매칭 시스템을 시뮬레이션하는 프로젝트입니다.

## 🛠 주요 기능
- **수요 예측 (Forecasting):** 과거 전력 사용량 데이터를 기반으로 시계열 예측 수행.
- **시장 매칭 (Market Matching):** 공급과 수요 곡선이 만나는 지점에서 SMP(계통한계가격) 결정.
- **시각화 (Visualization):** 시간대별 전력 수급 상황 및 가격 변동 그래프 출력.

## 📂 파일 구조 (이곳에 실제 파일 이름을 적어주세요)
- `predict_demand.py`: 전력 수요 예측 핵심 코드
- `market_matching.py`: 거래소 매칭 알고리즘
- `data/`: 시뮬레이션에 사용된 전력 데이터 샘플

## 🚀 시작하기
1. 필요한 패키지 설치:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   
