# 참고자료

[개념 사이트1](https://hleecaster.com/ml-logistic-regression-concept/) 설명: **  
[시그모이드 개념](https://icim.nims.re.kr/post/easyMath/64) 설명: **  
[개념 사이트2](https://nittaku.tistory.com/478) 설명: ***  
[실습 사이트](https://todayisbetterthanyesterday.tistory.com/11) 설명: *** - 프로세스 명확, sm모델 사용  


# 개념정리

## 정의
      -> 독립 변수를 로짓으로 변환하고 선형 결합을 이용하여 범주형(0 or 1)인 종속변수를 예측하는데 사용되는 통계 기법
      -> 최대우도추정 기법을 활용함
         -> 최대우도추정 기법: 관측값이 주어졌을 때 변수들 중 그 관측값을 발생시켰을 가능성이 가장 높은 매개변수값들을 거꾸로 찾아내는 과정

## 배경
      -> 선형회귀로는 결과값이 범주형인 종속변수를 fitting하기 어렵다.
         -> 잔차가 양극단 외에는 등분산성을 가짐
      -> 곡선으로 fitting하기 위해서 log(odds(1인확률 / 0인확률)) 형태로 `로짓변환`하여 사용
      -> odds란 각 독립변수에 대해 실패/성공에 대한 확률을 각각 구하는 것
      

## 핵심개념

### 로짓변환
    
      
      
