#### 더조은 컴퓨터 아카데미 '딥러닝을 이용한 주식 자동매매 프로젝트'입니다.
----
![pic1](https://user-images.githubusercontent.com/71945157/95052964-b7e21500-072a-11eb-80a1-8fd45293c0b0.png)
---
###### 주식시장에서 개인, 기관, 외인 수익률의 격차를 줄이고 감정을 배제한 완벽한 시스템 트레이딩을 위해 고안된 프로젝트 입니다.
###### 본 프로젝트는 백테스팅을 통한 신뢰도를 구축후 실투자에 적용할 예정입니다.
###### 배포는 웹 혹은 앱 어플리케이션 형태로 배포될 예정입니다.
###### 개인 투자성향에 맞춤 커스터마이징을 적용할 예정입니다.
###### 본 프로젝트는 주가를 분석/예측하는 al-1과 금융 뉴스기사의 텍스트 감정분석을 통한 al-2가 결합된 형태를 목표로 하고있습니다.
###### 본 프로젝트는 딥러닝 금융 플랫폼의 효시로서 추후 부동산매매, 원자재매매, 자산관리등 통합 시스템을 구축하는것이 최종 목표입니다.
---
##### 현재 진행상황
###### 데이터 수집(크롤링을 통한 뉴스기사, financedatareader를 이용한 주가데이터) --완료
###### API를 이용한 로그인/주문/잔고확인 기능 --완료
###### 주가데이터와 뉴스데이터를 데이터베이스에 저장 --완료
###### 누적된 데이터를 이용해 모델 학습 --진행중

---
##### 최신 진행 상황
---
#### LSTM을 이용한 삼성 주가데이터의  예측
---
![samsungtest](https://user-images.githubusercontent.com/71945157/95051761-bfa0ba00-0728-11eb-99e0-ae89d5641db6.png)
---
#### Talib을 이용한 보조지표 생성
---
![talib](https://user-images.githubusercontent.com/71945157/95061526-aacb2300-0736-11eb-8bbb-2c5306bed31f.png)


---
##### 이전 진행 상황
---
#### invest.com의 금융 뉴스기사 크롤링
---
![data1](https://user-images.githubusercontent.com/71945157/95054321-ae59ac80-072c-11eb-8dca-8ebd2b473127.png)

---
#### financedatareader open source package를 이용한 주가데이터,환율,코스피지수등의 데이터 수집
---
![data2](https://user-images.githubusercontent.com/71945157/95054506-ed87fd80-072c-11eb-88fb-2b2935465815.png)
---

---
#### 대신증권 API CYBOS Plus 를 이용한 과거 분단위 주식데이터 수집
---
- API 접속

![Cap 2020-10-05 17-02-27-126](https://user-images.githubusercontent.com/69662531/95057062-92f0a080-0730-11eb-8dfe-0326433438ac.jpg)

- 소스코드 

![Cap 2020-10-05 17-09-09-496](https://user-images.githubusercontent.com/69662531/95057190-c4696c00-0730-11eb-8afa-80a99940b2ab.png)

- 데이터 수집

![Cap 2020-10-05 17-06-29-139](https://user-images.githubusercontent.com/69662531/95057264-da772c80-0730-11eb-869c-1c4afcf126a7.png)

- 로컬 저장소에 .csv 파일로 저장

![Cap 2020-10-05 17-09-45-834](https://user-images.githubusercontent.com/69662531/95057298-ea8f0c00-0730-11eb-9f99-7e4b4087b27d.png)
