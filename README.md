# **성적기반 대학원 합격 예측 모델 개발**

## gre, gpa, rank 가 주어졌을 때 admin을 예측하라<br>

**테이블 정의서**: ‘admit’ : 입학 여부 0(탈락), 1(합격) , ‘gre’ : 영어점수, ‘gpa’ : 학점, ‘rank’ : 대학원 레벨 1(제일 높음) <br>

**과정** <br>
사용언어 & 라이브러리 : python 3.8x, tensorflow 2.7, numpy==1.21.4, keras==2.7.0, 

1. 데이터 전처리 : 결측치 처리(dropna())

2. 모델 생성 :  활성함수(tanh, sigmoid), 옵티마이저(adam), loss(binary_crossentropy), metrics(accuracy), epochs =1000

3. 예측 : model.predict

**결론** <br>

![1](https://user-images.githubusercontent.com/87745990/144752105-25e1fadd-f474-40b5-b6b0-45386d087b50.png)



