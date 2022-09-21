# KT_Devchall
KT Devchall 2022 공모전 참여를 위한 repository 입니다.

## 프로젝트 개요
온라인 광고 중개 플랫폼의 광고 경매 데이터를 활용하여,
해당 광고거래 입찰 내역이 낙찰(1)될 것인지, 유찰(0)될 것인지 분류하는 Binary Classification

## 분석 내용
1. Pandas Profiling 및 Kernel Density Estimation 등을 이용한 EDA로 변수 전처리 진행
2. `CatBoost` 이용, 부스팅 알고리즘에서 feature importance를 바탕으로 변수 간 상관관계 등을 종합적으로 고려한 변수 선택
3. `pytorch` 이용한 MLP 모델링