# README



### 파일구조

1. 네이버 리뷰 스크래핑

   파일명 : naver_movie_scraping.ipynb

2. 네이버 리뷰 데이터셋

   폴더명 : datasets

3. 감정 분석 모델링

   파일명 : RNN Semi-Project-team3-local.ipynb

   현재 : Embedding -> LSTM -> Dense, accuracy 80.01%

   목표 : 모델링 개선 (46번째 셀)
   
4. 토큰화, 모델링 분리

   파일명 :

   ​	01.RNN Semi-Project-Tokenization.ipynb

   ​		- dataset/naver_movie_all.csv 를 토큰화, save폴더에 작업 결과 저장

   ​	02.RNN Semi-Project-Evaluate.ipynb (csv파일 업데이트 없으면 이 작업만 하면됨)

   ​		- save폴더에서 토큰화된 데이터 읽은 후, 모델링

   