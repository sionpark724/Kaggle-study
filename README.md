# 2022-1 휴먼프밍 캐글 분석 STUDY

## 1주차 : Titanic - Machine Learning from Disaster 🚢

### - 데이터셋 :
![01](https://user-images.githubusercontent.com/79091824/158053990-25d8d7dc-6e75-4625-b6ca-e8ad0482674d.PNG)
#### feature는 Pclass, Age, SibSp, Parch, Fare 이며, 예측하려는 target label 은 Survived 입니다.

### - EDA :
#### 1. Pclass , Sex , Embarked 과 Survived 사이 관계
![2](https://user-images.githubusercontent.com/79091824/158059638-0e33d19a-df49-495b-a779-0c8b901b498a.png)
< Pclass 분포 , Pclass 별 생존자 분포 >
 
![3](https://user-images.githubusercontent.com/79091824/158059679-f0935070-8757-4f34-b59d-7a023d7f8f00.png)
< 성별에 따른 생존자, 사망자 분포 >
 
![4](https://user-images.githubusercontent.com/79091824/158059723-702b4a3f-621f-44be-943e-b7bc2d6b7449.png)
< 탑승 항구 위치에 따른 생존자, 사망자 분포 >
 

#### 2. Age, Fare 와 Survived 사이 관계
![5](https://user-images.githubusercontent.com/79091824/158059787-4a6274fe-c50f-4b24-91b3-063982a2f16c.png)
< 연령에 따른 생존자 분포 >
 
![6](https://user-images.githubusercontent.com/79091824/158059812-9fc71b2c-b916-4a05-b6d9-ce74f436a39a.png)
< 승선 요금에 따른 생존자 분포 >
 
#### 3. Family( Parch와 SibSp ) 와 Survived 사이 관계
![7](https://user-images.githubusercontent.com/79091824/158059865-ad39300f-3c75-42cd-a730-61ddcc9e7680.png)
< 가족 수에 따른 생존자 분포 >
 
### - 사용 모델 : 사이킷런의 RandomForestClassifier 모델 

### - 정확도 :
|데이터셋|정확도|
|------|---|
| Train |  83.21% |

      
### - Competition 링크 : [ 캐글 링크 ](https://www.kaggle.com/c/titanic)
      
### - 참고 자료 링크 : [ 1.Tutorial ](https://kaggle-kr.tistory.com/18?category=868316)
      
      
### - 참여자
@HyeJung-Hwang
