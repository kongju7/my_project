
# DS/AI 부트캠프 - 개인 프로젝트 개요 
(최신순)

* [두 번째 프로젝트]: 고객 이해를 바탕으로 한 프로모션 참여 예측
* [첫 번째 프로젝트]: 비디오 게임 출고량 분석 및 향후 전략
---
  
## [두 번째 프로젝트]: 고객 이해를 바탕으로 한 프로모션 참여 예측 
- 작성: 2022년 9월 30일   
- 코드 파일: [ai_15_공주_s2_code.ipynb](https://github.com/kongju7/my_project1_2/blob/main/ai_15_%EA%B3%B5%EC%A3%BC_s2_code.ipynb)


### 개요

1. 데이터 탐색 및 문제 정의 
    - 데이터 소개: (유통 업체) 고객 및 구매 정보 데이터 → 시나리오 
    - 문제 정의 및 가설
      - '중요 고객(Royal customers)' 정의 및 규모, 특성 파악 
      - 프로모션 행사 참여 여부 예측 모델링
    - 데이터 탐색 및 전처리 과정 
   
2. 고객 이해
    - 평균적인 고객 특성: 40대, 대졸, 3인 가구 
    - (RFM 기반) '중요 고객' 정의: '중위값' 이상,  K-Means Clustering
    
    <img src = "https://raw.githubusercontent.com/kongju7/my_project1_2/main/img/s2_clustering.png" width="50%" height="50%">   
    
    - '중요 고객' 특성: 일반 고객과 평균 비교 
      - 인구학적 특성: 소득 수준은 40% 높고, 자녀 수는 30% 적음
      - 구매 특성: 전 품목 구매량, '카탈로그' 구매, 기존 프로모션 참여 횟수 2배 이상 많음 → 구매 여력이 있는 적극적인 구매층 
    <img src = "https://raw.githubusercontent.com/kongju7/my_project1_2/main/img/s2_comparison.png" width="60%" height="60%">

3. 프로모션 참여 여부 예측 
    - 분류 예측 모델링: 트리 기반 부스팅 모델 + 베이지안 기반 하이퍼파라미터 튜닝 
    - 모델 일반화 검증 및 해석: PDP 활용

4. 분석결과 요약 및 제언: 이번 프로모션 및 중장기 전략 
    - 이번 프로모션 행사 마케팅 전략
      - 최근 두 달 내 구매 기록이 있고, 
      - 과거 프로모션 참여 경험이 많은 고객을 집중 타겟으로 프로모션 진행 
   
    - 중장기적 전략
      - '중요 고객' 중 프로모션 행사 참여가 없거나 최근 구매가 없는 고객 대상  
      - 상점이나 카탈로그 쿠폰 발행 등 ‘중요 고객’ 선호 기반 별도 프로모션 추진 
      - 고소득층 2~3인 가구 생활양식에 적합한 추천 시스템 구축
  
---    
     
## [첫 번째 프로젝트]: 비디오 게임 출고량 분석 및 향후 전략
- 작성: 2022년 8월 29일 
- 코드 파일: [ai_15_공주_s1_code.ipynb](https://github.com/kongju7/my_project1_2/blob/main/ai_15_%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%AE_s1_code.ipynb)


### 개요 

1. 데이터 탐색
    - 지정 데이터: 비디오 게임 출고량 데이터 (출처: 캐글)
    - 데이터 전처리 및 탐색 과정
  
2. 연도별 비디오 게임 트렌드: 전체 / 지역 / 플랫폼 / 장르 
    - 전체 경향: 비디오 게임 시장 쇠퇴
    - 지역별 출고량 점유율: 북미 → 유럽 이동
    - 플랫폼: 다양화, 닌텐도 강세
    - 장르: 명불허전 'Action'

3. 지역별 선호 비디오 게임 장르
    - 명불허전 'Action'
    - 일본의 독특한 선호도

<img src = "https://raw.githubusercontent.com/kongju7/my_project1_2/main/img/s1_share.png" width="50%" height="50%">

4. 출고량 높은 비디오 게임 분석
    - 상위 1% 비디오 게임
    - 역대 최고 출고량 게임: Wii SPORTS

5. 비디오 게임 군집화: 지역별 출고량 분석
    - K-Means Clustering

<img src = "https://raw.githubusercontent.com/kongju7/my_project1_2/main/img/s1_scatter.png" width="50%" height="50%">

6. 분석결과 요약 및 제언: 단기 및 중장기 전략
    - 다음 분기 비디오 게임 출시 전략 제언:
      - '닌텐도' 기반의 '액션' 게임
      - 성장 중인 '유럽' 시장 집중 공략 필요
    
    - 중장기적 전략:
      - '모바일' 게임 시장 분석 및 확대 필요
 
