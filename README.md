📃 About
===============

## 🚀 Tech stack
- JavaScript(ES6)
- TypeScript
- React, Redux, Redux-saga
- Express
- MongoDB, Mongoose

## 🎓 학력
- 서울대학교 원자핵공학과 학사 졸(2012.02)

## 🏦 경력

- 현대건설(주) [2012 - 2015]
- 한국원자력안전재단 [2015 - 재직중]

<br>

# 💻 개인 프로젝트

## **✏️ Blog project** (2020.05 - 2020.07) (TypeScript)

### **[Repository]**

 | 구분          | Link                                             |
 | :----------- | ----------------------------------------------- |
 | **frontend** | https://github.com/goonerholic/my-blog-frontend |
 | **backend**  | https://github.com/goonerholic/my-blog-backend  |
 | **product**  | http://common-labour.gq                         |
 
  
### **Backend**
- Express를 활용한 회원인증, 포스트관련 Route 구현
- jwt기반 인증 구현
- MongoDB, Mongoose를 활용한 CRUD 기능 구현
- Morgan을 활용한 API request에 대한 로그 기록
- API Request에 대한 테스트 코드 작성(Jest)

### **Frontend**
 - Redux, Redux-Saga, Typesafe-actions를 활용한 상태관리
 - React-router-dom을 활용한 클라이언트 사이드 라우팅 구현
 - React-quill(quill wrapper for react)을 통한 포스트 작성, 수정 기능 구현
 - Sass, materialize-css를 활용한 컴포넌트 스타일링

### **Deployment**
 - 구글 클라우드 플랫폼 컴퓨팅 엔진 활용
 - Nginx forward proxy를 통한 api 서버 및 react 정적파일 분리
 - PM2를 활용한 프로세스 관리
  
### **Reference**
   - 리액트를 다루는 기술(김민준, 2018)

<br>

## **📊 Bitmex-candle-emitter** (2019.12 - 2020.01) (JavaScript)
> **[Respository]** https://github.com/goonerholic/my-blog-frontend  
 - Bitmex Websocket API를 활용한 캔들데이터(ohlc) 생성기
 - websocket을 통해 거래데이터를 저장하고 cronjob을 통해 설정된 timeframe에 따른 캔들데이터 생성
 - event emitter를 활용하여 생성된 candle data emit

<br>


## **📊 Bitmex-backtester-backend** (2020.01 - 2020.06) (TypeScript)
> **[Respository]** https://github.com/goonerholic/bitmex-backtester-backend
 - Bitmex backtesting을 위한 backend 구현
 - Bitmex REST API를 활용한 candle data불러오기 및 저장(mongodb)
 - Candle data 및 technical indicator 저장을 위한 dataframe 구현
 - 거래 전략 저장을 위한 query schema 구현 및 query파싱 함수 구현
 - 전략 조회, 저장, 수정을 위한 route구현(api/strategy)
 - 백테스트 실행을 위한 route구현(api/backtest)
