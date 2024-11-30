# Machine5

## 프로젝트 구조
  모델 파일명 통일을 해야할 것 같습니다

## 프로젝트 개요와 해석
  1. 시나리오 1: 모든 데이터를 합쳐서 rf
    각각의 데이터셋의 특성이 다른데 그걸 반영하지 못해서 낮은 정확도를 보인다.
  2. 시나리오 2: 바이너리->멀티 예측  
    데이터셋 특성을 잘 반영하였고 정확도가 높게 나왔으나, 데이터셋의 불균형(-1:나머지 95개 클래스 = 10000:19000)이 매우 심해서 ROC, PR스코어가 매우 낮게 나왔다.  
    해결방안: Oversampling/Undersampling 등의 기법으로 클래스 균형 조정이 필요해 보인다.
석
## 실행방법
* 파일 수가 많아서 깃헙 레포를 복제해서 로컬로 돌리는 방식을 제시할지   
* 아니면 그냥 데이터셋 다운받아서 코랩으로 쓰는 방식을 제시할 지 고민중  
* (몇몇 코드들 실행방식에 따라 데이터 로드하는 부분 고쳐야 함, 아마 후자로 할 것 같습니다)

## 팀원/역할
|[Minseo Kim](https://github.com/440g)|[Chaewon Kim](https://github.com/chaewonni)|[Minkyung Song](https://github.com/miikii41)|[Seungyeon Kim](https://github.com/bleuxsy)|[Yeonsu Kim](https://github.com/sooooscode)|
|:---:|:---:|:---:|:---:|:---:|
|역할|역할|역할|역할|역할|