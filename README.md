# ☕원두 분류하기

## Description
📌2022 Artificial Intelligence Team Project                                                                                                               
  🕰️2022.11.14~2022.12  

## 🧜‍♀️Member
**kim**👩‍💻:주제 선정 및 데이터 확보, 이미지 증강 및 분류, 이미지 전처리 및 모델 학습, 모델 학습 적용                                                                        
**Jeong**👩‍💻:주제 선정 및 데이터 확보,이미지 분류, 모델학습 및 적용, 웹 페이지 구현                                                                                     
## System configuration
 **데이터 크롤링** ➡️ **데이터 확보 및 데이터 처리** ➡️ **모델 학습** ➡️ **웹 페이지 구현**                                                                                    
- 데이터 크롤링 : 구글 및 네이버 크롤링으로 데이터 확보                                                                                                          
- 데이터 확보 : train(1277장)과 validation(452장)으로 진행                                                                                                     
- 데이터 전처리 : ImageDataGenerator 와 train.flow_from_directory 사용                                                                                                                                                                               
- 모델 학습 : 전이학습 이용 (VGG16모델 사용하여 학습 ->데이터 부족으로 인하여)                                                                                    
- 웹페이지 구현 :Flask 이용



### Main Function
-원두 이미지를 넣으면 원두 로스팅된 상태를 알려줌                                                                                                                                         

## About Project                                                                                                                          
<img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><br>

### Result
<p align="center"><img src="https://github.com/jeongYuri/Classification_of_beans/assets/74125993/b8397d25-8f2e-4993-b0ad-31136b9d1559.png" />
<p align="center"><img src="https://github.com/jeongYuri/Classification_of_beans/assets/74125993/edf5b674-020d-4ca3-9213-22ae37ecab7b.png" />
<p align="center"><img src="https://github.com/jeongYuri/Classification_of_beans/assets/74125993/b2952f5d-b6f5-4fcd-b214-ec8758d44652.png" />

