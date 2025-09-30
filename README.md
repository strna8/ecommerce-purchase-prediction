# ecommerce-purchase-prediction

# 🛒 AI 기반 E-commerce 고객 구매 예측 모델
온라인 쇼핑몰 고객 데이터를 활용하여 **구매 여부(Revenue)를 예측**하는 머신러닝 프로젝트입니다.  
Decision Tree, Random Forest 등 다양한 알고리즘을 적용하고, 주요 변수(Feature Importance)를 분석했습니다.

---

## 📊 프로젝트 개요
- **목표**: 고객의 행동 데이터를 기반으로 구매 가능성을 조기 예측  
- **데이터셋**: Kaggle - [E-commerce Shopper's Behaviour Understanding]  
- **기대효과**: 
  - 마케팅 효율성 제고
  - 잠재 고객 조기 식별
  - 광고 비용 최적화

---

## 📂 데이터 개요
- **행(row) 수**: 12,330  
- **컬럼(column) 수**: 18  
- 주요 변수:
  - `PageValues`: 페이지의 경제적 가치
  - `ExitRates`: 고객 이탈 비율
  - `ProductRelated_Duration`: 상품 관련 페이지 체류 시간
  - `VisitorType`, `Weekend`, `Month` 등  

---

## 🛠️ 분석 과정
### 1. 데이터 탐색(EDA)
- 결측치 없음 확인  
- 주요 범주형 변수 분포 시각화 (`VisitorType`, `Weekend`, `Month`)  
- `Revenue` (구매 여부) 클래스 불균형 확인 (약
