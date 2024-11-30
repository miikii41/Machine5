# Machine5

## Project Structure

<details>
<summary>Machine5</summary>
<div markdown="1">

  ```
    Machine5
    ┣ Closed
    ┃ ┣ baseline.ipynb
    ┃ ┣ Closed_RF_old.ipynb
    ┃ ┣ Closed_RF_selected10.ipynb
    ┃ ┣ Closed_RF.ipynb
    ┃ ┗ Closed_SVM.ipynb
    ┣ Open_Binary
    ┃ ┣ baseline
    ┃ ┃ ┗ Open_Binary_KNN.ipynb
    ┃ ┣ binary_labels.csv
    ┃ ┣ Open_Binary_SVM.ipynb
    ┃ ┣ Open_Binary_RF.ipynb
    ┃ ┣ Open2_Binary_RF_selected6.ipynb
    ┃ ┗ Open2_Binary_RF_selected12.ipynb
    ┣ Open_Multi
    ┃ ┣ Open_Multi_RF.ipynb
    ┃ ┣ Open2_Multi_RF.ipynb
    ┃ ┣ Open_Multi_SVM.ipynb
    ┃ ┗ final_labels.csv
    ┣ features
    ┃ ┣ feature_information
    ┃ ┃ ┣ combined_feature_information.ipynb
    ┃ ┃ ┣ comimage.png
    ┃ ┃ ┣ comimage2.png
    ┃ ┃ ┣ mon_feature_information.ipynb
    ┃ ┃ ┣ monimage.png
    ┃ ┃ ┣ monimage2.png
    ┃ ┃ ┣ unmon_feature_information.ipynb
    ┃ ┃ ┗ unmonimage.png
    ┃ ┣ modified_datasets
    ┃ ┃ ┣ feature_generator.ipynb
    ┃ ┃ ┣ mon_features.csv
    ┃ ┃ ┣ mon_features_old.csv
    ┃ ┃ ┣ mon_labels.csv
    ┃ ┃ ┣ unmon3000_features.csv
    ┃ ┃ ┣ unmon3000_features_old.csv
    ┃ ┃ ┣ unmon_features.csv
    ┃ ┃ ┗ unmon_features_old.csv
    ┃ ┣ original_datasets
    ┃ ┃ ┣ mon_standard.pkl
    ┃ ┃ ┣ unmon_standard10.pkl
    ┃ ┃ ┗ unmon_standard10_3000.pkl
    ┃ ┗ README.md
    ┗ README.md
  ```
</div>
</details>


## Overview
  1. 시나리오 1: 모든 데이터를 합쳐서 rf
    각각의 데이터셋의 특성이 다른데 그걸 반영하지 못해서 낮은 정확도를 보인다.
  2. 시나리오 2: 바이너리->멀티 예측  
    데이터셋 특성을 잘 반영하였고 정확도가 높게 나왔으나, 데이터셋의 불균형(-1:나머지 95개 클래스 = 10000:19000)이 매우 심해서 ROC, PR스코어가 매우 낮게 나왔다.  
    해결방안: Oversampling/Undersampling 등의 기법으로 클래스 균형 조정이 필요해 보인다.
석
## Usage
* 파일 수가 많아서 깃헙 레포를 복제해서 로컬로 돌리는 방식을 제시할지   
* 아니면 그냥 데이터셋 다운받아서 코랩으로 쓰는 방식을 제시할 지 고민중  
* (몇몇 코드들 실행방식에 따라 데이터 로드하는 부분 고쳐야 함, 아마 후자로 할 것 같습니다)

## Contributors
|[Minseo Kim](https://github.com/440g)|[Chaewon Kim](https://github.com/chaewonni)|[Minkyung Song](https://github.com/miikii41)|[Seungyeon Kim](https://github.com/bleuxsy)|[Yeonsu Kim](https://github.com/sooooscode)|
|:---:|:---:|:---:|:---:|:---:|
|역할|역할|역할|역할|역할|