# Machine_Learning_Project_2

- 본 프로젝트는 "포켓몬" 이미지 데이터를 머신러닝을 활용하여 학습시켜서 "포켓몬"을 분류하는 모델을 만드는 것을 목표로 하였습니다.
- 저는 포켓몬 중에서도 4세대 포켓몬(신오지방) 분류 모델을 만드는 것을 목표로 하였고, 앙상블 모델 중 하나인 RandomForest 알고리즘을 선정하여 학습을 진행하였습니다.

## 🔧 사용한 기술

- Python
- Pandas
- Numpy
- sklearn
- cv2
- rembg

## 📂 활용 데이터셋 출처

- 포켓몬 공식 사이트 (https://pokemonkorea.co.kr/pokedex)
- 포켓몬 도트 그래픽 제공 사이트 (https://pokemondb.net/pokedex/game/diamond-pearl)

## 📂 파일 설명 

- pokemon_image_last : 이미지 데이터 증강 및 CSV 파일로 변환
- pokemon_model_2.ipynb : RandomForest 알고리즘을 활용하여 포켓몬 분류 모델 생성
- web.zip : 웹 구현 파일 (model_ 파일에는 저장한 모델을 추가하면 됩니다.)

## 🎯 프로젝트 목표 

- 이미지 데이터 증강해보기
- 이미지 데이터를 CSV 파일로 변환하여 머신러닝 학습 적용
