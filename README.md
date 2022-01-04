# Description
본 프로젝트의 데이터셋은 특정 행정동에서 0시~24시까지 하루 동안 커피분야의 매장에서 소비를 일으킨 성별 연령대별 고유 인구의 수를 제공합니다. 

# Evaluation
![RMSE](https://blog.kakaocdn.net/dn/b10oWd/btqBxATyHHi/QWuTvEd3FBMh5BfmkUVVCk/img.png)

# Data
데이터셋은 https://www.bigdata-environment.kr/ 에서 제공하는 "행정동별 커피분야 소비인구" 데이터입니다.
<br><br>
gov_dn_cd, bntr_nm, signgu_nm, adstrd_nm, de, sex_se, year_se, cnsmr_popltn_co 정보로 구성되어있으며
<br><br>
이를 이용하여 커피 소비인구를 예측 할 수 있습니다.
<br><br>

|컬럼|설명|
|---|---|
|gov_dn_cd|행정동코드|
|bntr_nm|시도명|
|signgu_nm|시군구명|
|adstrd_nm|행정동명|
|de|기준일자|
|sex_se|성별|
|year_se|연령대|
|cnsmr_popltn_co|소비인구|


# Kaggle
### [Kaggle Competition](https://www.kaggle.com/c/coffeecsmr/data)에 참여해보세요 !<br>


# Model

데이터 분석은 거의 하지 않은 상태로 모델을 만들었습니다. <br>
따라서 의미있는 데이터 분석을 수행한 값을 모델에 넣어준다면 더 좋은 성능을 기대할 수 있습니다.
