## 'AYO CRYPTO HOT 10' 고려대학교 Design Thinking 과제 프로토타이핑 데모 S/W

__개발환경__
- 메인 프로그램: NATIONAL INSTRUMENTS Co. LabVIEW Development System 2017 이상
- 코인마켓캡 Open API 프로그램: Python 3.11.1 이상
- 비트코인 종가 분석 EDA 프로그램: Samsung SDS Brightics AI

---
## 메인 프로그램 installation
__First step__
- 소스코드는 전체를 다운로드 후, 'ayo' 폴더를 c드라이브 아래에 위치 시킨다.

__Second step__
- 실행파일을 실행하기 위해서는 LabVIEW run-time engine 2017이상을 설치해야 한다. 
[apiLink](https://www.ni.com/ko-kr/support/downloads/software-products/download.labview-runtime.html#460613) 로 가서 2017 또는 그 이상을 설치한다.  

## 코인마켓캡 top 100 listing data Open API 파이썬 프로그램 installation
__First step__
- C:\ayo\python
- pip install -r requirements.txt

__Second step__
- you should get a apikey from coinmarketcap link [apiLink](https://coinmarketcap.com/api/)

__Third step__
- if you have environment variable named "apiKey" in your environment file or in your local system, then just just activate python file

    > python getTop100CoinData.py
- or if you don't have environment variable named "apiKey", you should give apikey in the prompt parameter when you activate python file  

    > [example this is fake apikey] python getTop100CoinData.py cbb35343-71fe-4351-ac57-e3c8cb7c296c
    
__Fourth step__

- you can get a list data that is same with coinmarketcap main page. you can slice each data with comma ',' . 


## 메인프로그램 실행하기
__메인프로그램실행__
- C:\ayo\exe\ayo_crypto의 ayo_crypto.exe를 실행한다.
- 첨부되는 user_manual.pdf 메뉴얼을 보고, 스텝별로 따라서 데모 프로그램을 조작한다.

__코인마켓캡 CRYPTO 데이터 가져오기__
- 아래 그림 OPEN_API_CHART 탭으로 이동한다
- ![image](https://user-images.githubusercontent.com/120719360/208230287-40dace09-8a2e-40a6-afb4-f7825e3718ce.png)
- 스크롤바를 내려서 좌축 파일선택 상자에는 설치한 파이썬 실행파일을 선택하고, 우측에는 C:\ayo\python의 getTop100CoinData.py를 선택한다. 
- ![image](https://user-images.githubusercontent.com/120719360/208230420-88bd3f9f-7e1e-490f-b97b-2df524fd194e.png)

__비트코인 종가분석 프로그램 실행하기__
- C:\ayo\Brightics_EDA
- 사용하고자 하는 사람은 https://www.brightics.ai/를 통해 사용방법을 숙지하고, bitcoin_price_predictiom.json파일을 로딩하여 사용한다. 

