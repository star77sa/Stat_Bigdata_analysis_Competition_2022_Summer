# Stat_Bigdata_analysis_Competition_2022_Summer
[전북대학교 통계학과 빅데이터 분석 경진대회(2회)](https://www.kaggle.com/competitions/statjbnu202207/overview), 우수상

--- 
자세한 내용은 ppt 참고바랍니다!

코로나 데이터를 분석하는 문제.

'감정'에 초점을 맞추어 문제 분석 및 해결방안을 제시

코로나 누적 확진자수와 월별 온라인 카드 소비 / 월별 자살자수와 월별 온라인 카드 소비가 매우 높은 상관관계를 보임

- 언론에서의 부정적 단어들은 수용자들에게 부정적 감정을 일으킨다.

- 코로나 이전에 비해 부정적 기사가 1.73배 증가했다.

## 문제인식

감정소비와 우울증에 관한 대책마련 필요성을 느낌

## 해결방안 제시
1. 코로나19 관련 기사를 분류
2. 기사의 긍·부정을 분류
3. 긍·부정적 기사의 노출 순서를 조절

## 1. 코로나 19 관련 기사 분류
- 데이터는 공공데이터 포털에서 제공하는 뉴스 빅데이터를 전처리하여 사용
- 분류모델은 BERT 사용
- 각 분야별 뉴스 6800개와 코로나 관련 기사 4000개를 훈련자료로 사용

![image](https://user-images.githubusercontent.com/73769046/181712448-7b42c4a0-ee4e-43af-99b3-b7210307cdea.png)

## 2. 기사의 긍·부정 분류
- KNU 감서사전을 이용하여 부정어 구축
- Train 데이터 긍·부정 분류, 라벨링 후 학습

![image](https://user-images.githubusercontent.com/73769046/181712683-578465c1-9aa4-4169-96ac-28c44148d8e8.png)
![image](https://user-images.githubusercontent.com/73769046/181712715-8ba76a08-9ce6-4606-96b0-61a02ea62f9e.png)

## 정리
![image](https://user-images.githubusercontent.com/73769046/181712782-0350082d-ad63-4f6f-94e2-372481775fbb.png)
