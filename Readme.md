# PORTFOLIO



### 5. [진행] 개인 과외  2020.01.01 ~ (진행중)

[2020 과외 진행사항](https://github.com/Phantom05/work_project)

### 4. [종료] 개인 과외 2018.12.23 ~ 2019.11.31 (12개월)

[2019 과외 종료](https://github.com/Hello-Programing/Kizi-Refo)




### 3. DOF 연구소, 개발팀, 2018.05.01 ~ 재직중, 연구원, 프론트개발

**BUILT WITH**
React, Redux, Redux-saga, Mobx, Websocket, Webworker, qwebchannel, Webpack, Nodejs, Gulp, AWS로 개발하였습니다.

**CONCEPT**
심도 깊은 자바스크립트 연구를 하기 위해 노력했습니다.

**PROJECT MANAGEMENT**

Private Gitlab.

**USE STACK**

- CM - Git, Gitlab
- Mark Up - Accessibility, Standardity, SEO, HTML5, Semantic
- Css - CSS3, CSS2, Css/Scss, Response, Adaptive, Cross Browsing( Level >= ie7 ), Grid layout, Flex, Box model, Position, Float, BEM, Animation, ,Css Module,
- Scss Stack : Function, If, Mixin, Mapping, Nest, Anpercent, Variable, inShap, Scope, extend, import, flow controls, Flag, iter
- Nodejs - gulp, lodash, passport, https, express, redis, axios, unirest, multer, react(part), express-session, cashing, crawroling, Meth.js, firebase, mysql, NODE_ENV, async, promise, xss, runscript, babel, i18n, uuid, bcrypt, helmet, os, axios, kill-port, morgan, node-cron, nodemailer, cookie-session, better-npm-run, env preset, winston, logger, npm script, axios, promise, babel, http, helmet, node-cron, nodemailer, os, utf8, async,  ...
- Bundler - Gulp, Webpack, Npm, Yarn
- FrameWork - Express, Bootstrab
- library -  Semantic UI, JQuery, Many Graph Charts,
- Javascript - ES6, ES7, ES8, DOM API, Event Loop, Anysn Await, Promise, None-blocking I/O, Http Shadow, Browswer Workd, Prototype, Cluster, cors, Https, Ajax, Axios, Xss, Amp, common js, GraphQL, Single Thread, Rest API, Restful API, eslint, prettier, npm script, taskrunner, Pattern( module, factory ... 
- Crontab, Linux Scheduling

- Communication -  Microsoft daouoffice, Microsoft Teams, Postman, Zira, Figma, Adobe xd, Google spreadsheets, Sourcetree, Google Analytics, Todolist, Markdown MD, MD Documentation

**USE FUNCTION.**

+ C++ 과 연동한 비인터넷 상황 데이터 통신 모듈 개발
+ C++ 연동 관련 모든 통신을 Web worker, Socket.io를 이용한 양방향 통신 모듈 개발
+ 페이지 3개를 한화면에 연동
+ Clusting, Debounce를 사용한 비동기 웹 치아 프로그램 모듈 개발
+ Socket.io를 이용한 채팅 개발 (사진전송 가능)
+ 70페이지 분량 홈페이지 프론트 개발

**PROJECT SUMMARY.**

1. ***Electron Launcher***

+ React를 기반으로 일렉트론을 활용한 프로젝트를 진행하였습니다. Reduc-saga와 flux패턴을 사용하여 Container Component들을 두고 최대한 재사용성을 고려하여 개발을 진행 하였으며, 프리젠테이션 컴포넌트를 두고 프리젠테이션 컴포넌트를 감싸는 웨퍼 컴포넌트를 둔 후 이벤트 타입시스템을 적용 해봤습니다. *이벤트 타입 시스템음 제가 직접 붙힌 이름입니다. 기존에 컨테이너와 프린젠테이션 컴포넌트가 묶여있을 경우 State 의존성이 강해 컨테이너가 많이 지저분해지는 경험을 했었습니다. 하지만 이벤트 타입 시스템을 적용하여 웨퍼 컴포넌트에서 이벤트를 걸 경우 웨퍼로 묶인 컴포넌트의 value들이 이벤트 발생에 따른 값들을 객체로 반환해주는 패턴을 사용해봤습니다. 해당 패턴을 진행 했을 경우 재사용성과 빠른 유지보수의 만족도가 높았습니다. 또한 프리젠테이션 컴포넌트의 경우 모든 프로젝트의 공용 Git 레파지토리를 하나 생성해 클론받아 모든 프로젝트에 사용될 수 있게끔 최대한 다형성과 재사용성 있게 만들어서 클론하여 사용하였습니다. 이때 다수의 프론트엔드 개발자분들과 함께 만들었기 때문에, 주석이나 함수명에 대한 컨벤션이 중요하였고 프리젠테이션 컴포넌트의 레파지토리가 커질수록 폴더명과 파일스트럭쳐 또한 중요하여서 회의를 진행하였습니다. 데이터 통신으로는 리덕스 사과와 알림과 메세지, 네트워크 환경 정보를 받을땐 소켓을 통신하여 진행하였습니다. 리덕스 사가의 경우 최대한 프로그램적으로 동작하기 위해 pending, success, failure 패턴을 사용하였으며 액션이 과도하게 많아져 액션들을 객체로 묶고 객체를 함수에 담아 단 2줄의 코드로 액션, 사가미들웨어요청을 할수 있게끔 개발하였습니다. Reduc-saga와 api,. reducer는 최대한 가볍게 진행하고 데이터 흐름을 파악할 수 있도록 개발하였으며, 비즈니스 로직의 경우 대부분 컨테이너에서 처리하게끔 진행하였습니다. 각 컨테이너에서는 비즈니스 로직을 처리하기위한 파일을 뺴서 진행하였으며, 비즈니스 로직을 파악할땐 process.라는 폴더안에서 처리를 진행하였습니다. 리듀서 모듈을 붙힐떈 처음엔 페이지네임으로 페이지마다 통신을 진행하였는데, 기획상 페이지의 변경이나 기능이 변경될때 컨테이너와 리덕스를 동시에 수정해야하는 불편함으로 리듀서 모듈의 경우 기능을 중심으로 파일을 나눴습니다. 또한 Container Component들의 경우 리덕스와의 의존성을 최대한 배제하기 위해 hoc를 자주 만들어서 진행하였으며, 페이지 이동에 따른 커스컴 hooks들도 만들어서 진행하였습니다. 프론트엔드 메인 개발자로써 Git Branch전략을 Git flow를 세워 진행하였으며, 여러 프론트엔드 개발자분들이 푸쉬, 풀리퀘스트를 진행하며 아침 10시마다 기능 마무리를 하여 머지하고 컴플릭트가 났을경우에 상의하며 처리해나갔습니다. React 개발이 완료 된 후 일렉트론에 접목시켜 exe프로그램을 진행하였으며, 인스톨러까지 포팅하여 개발하였습니다.

2. ***Oral Scanner***

+ React, Redux, Redux-saga, Middleware, styled-components, immer, axios, qwebchannel, throttling, debouncing, Websocket, Webworker, Nodejs, lodash, AWS 등등..의 기술을 활용하였습니다. Redux-saga의 경우 추후 클라우드 서비스를 위해 도입하였고 모든 데이터 통신은 Saga Middleware들을 거쳐 서버와 통신을 진행하였습니다.React의 Hooks를 통해 개발하였으며 Custom Hooks들을 생성하여 보다 범용적으로 사용하도록 노력했습니다. 구강 스캐너 프로젝트의 경우 IOS 인증과 데모 버전까지는 모두 Websocket으로 통신을 진행해왔습니다. Websocket의 경우 통신 엔드 포인트가 1개뿐이라 해당 엔드 포인트에서 다시 모듈로 데이터들을 가져온 다음 각 역할에 해당하는 클래스들에 재 매핑을 하여 리드 서로 데이터를 가공하여 보낸 후 반응형 프로그래밍을 구축하였습니다. 하드웨어 장비에서 일방적으로 배터리 상태부터 이미지 데이터 등 받아야 할 데이터가 많기 때문에 해당 기술들을 채택하여 개발을 진행하였고 빌드부터 배포까지 진행하였습니다. 보다 확장성 있는 컴포넌트를 위해 프런트엔드 단과 C++ 단은 최대한 순수한 컴포넌트들로 구성하였으며 프로젝트마다 컨테이너 폴더들을 교체하고 컴포넌트들은 프레젠테이션 패턴으로 사용하게끔 구성하였습니다. 중간에 Node Server가 있는데 이 부분에서 대부분의 비즈니스 로직의 처리 후 약속한 통신 프로토콜을 이용한 데이터 통신을 진행하였습니다. json의 통신 비용을 절감하기 위해 IOS 인증 규격에 맡는 프로토콜로 통신을 진행하였습니다. 리액트에서 이벤트가 발생하여 서버로 데이터가 전달될 땐 리액트에서 이벤트를 감지하고 특정 모듈로 이벤트를 모아 통신 프로토콜에 해당하는 클래스들로 데이터를 전달하였고, 해당 클래스에선 데이터를 가공 후 서버단으로 전송하였습니다. 부하가 발생할 거 같은 이벤트들엔 대부분 디바운싱처리를 진행하였으며, 스크롤 이벤트 같은 경우는 쓰로틀링을 적용하였습니다. 메모제이션을 사용하여 리액트 렌더링을 최적화하였습니다. 또한 SSR을 구축하였으며 SSR 구축의 경우 express로 진행하였다가 여러가지 이유로 next.js로 변경하여 진행하고 AWS에 배포하였습니다.



3. ***Design Platform***

+ Nodejs, express, ejs , axios, scss, Websocket, lodash, debouncing, trottling, jQuery, bootstrab, gulp, webpack , AWS 등등..의 기술을 활용하였습니다. 백엔드 서버와, 프런트 서버로 구성되어 있는 구조로 진행하였으며, 프런트 라우터를 거쳐 ejs 템플릿 엔진에서 렌더링을 진행하였습니다. 대부분의 템플릿 엔진과 다르게 자유로운 ejs 템플릿 엔진으로 인해 모듈화가 필요했으며 Nodejs의 ejs locals에 라이브러리 형식으로 파일을 임포트 하여 각 클래스들을 사용하였습니다. 리액트처럼 좋은 CRA 자동 Webpack이 따로 존재하지 않고 엔트리 파일이 여러 개인 관계로 Gulp를 채택하여 진행하였으며 Import가 진행되는 js 파일 모듈 들은 Webpack을 통하여 빌드 하였습니다. 기본적으로 트리 셰이킹 모듈을 이용하여 사용하지 않는 함수들은 빌드 때 제거해주었으며, Back-end의 개발 속도가 뒤처질 경우 테스트 서버를 구축해 통신 테스팅을 이어 나간 후 데이터 정합하는 방식으로 개발하였습니다. 깃허브의 칸반 보드를 이용해 프로젝트 일정을 관리하였습니다. 템플릿이라는 파일들을 두어 각 페이지들을 관리하였으며 템플릿 파일의 매개변수들로 임포트 한 페이지들을 렌더링 하여 보다 체계적인 관리를 이어 나갔습니다. 대부분의 각 페이지의 js는 싱글톤 패턴을 이용하여 개발을 진행하였으며, 로그인 구현 시 jwt을 이용하여 프런트엔드 세션을 이용하여 백엔드 서버와 통신하여 처리하였습니다. 리퀘스트를 최대한 줄이는 일반적인 프로젝트와 다르게 해당 프로젝트의 경우 백엔드를 최대한 재활용하려고 그래프 QL과 같은 프런트에서 데이터를 요청하는 식으로 서버를 구성하였습니다. 데이터베이스 테이블을 최대한 잘 개 나눈 다음, 원하는 데이터를 프런트 라우터에서 여러 군데의 api로 요청하여 데이터를 모은 다음 렌더링을 진행하였습니다. 비동기 통신 관리를 위해 axios, promise, asyne await을 이용하여 통신을 진행하였습니다.
    



<br><br>

### 2. Dashboard Project  (중지 - 풀스택)

![468484584](https://user-images.githubusercontent.com/33567964/55025415-3cd37500-5044-11e9-96f4-681e7ce84e34.png)

![erherhwerhw](https://user-images.githubusercontent.com/33567964/55092374-d7d85780-50f5-11e9-9a49-44f63a5754ee.png)

![34634623423523](https://user-images.githubusercontent.com/33567964/54540369-3d806180-49db-11e9-9cc3-e119b77edf90.png)


![rtjrtjrtjeew](https://user-images.githubusercontent.com/33567964/55092382-dad34800-50f5-11e9-82e5-56c794cced2a.png)


![rtjrtjeje](https://user-images.githubusercontent.com/33567964/55092380-d9a21b00-50f5-11e9-91ae-b4dfe39c1df9.png)

![etjetje](https://user-images.githubusercontent.com/33567964/55092384-dc047500-50f5-11e9-994f-85cc3cdb8f20.png)

<center>
  <img src="https://user-images.githubusercontent.com/33567964/55139227-96d55700-5178-11e9-9a94-580a1569ff7c.gif" style="width:90%;margin:'auto'">
</center>

**BUILT WITH**
Express, MySQL, Nodejs, Gulp, AWS로 개발하였습니다.

**CONCEPT**
홈페이지, 대쉬보드에 들어가는 모든 기능을 담아보려고 노력했습니다.

**DEMO**

[Dashboard Proejct 바로가기](http://13.209.89.204:9000/)
**AWS 비용 청구로 서버 빼놨음, GCP로 이전 작업 중**

**PROJECT MANAGEMENT**

[Management 바로가기](https://github.com/users/Phantom05/projects/1)

**USE STACK**

- CM - Git, Github, Gitlab, Bitbucket
- Mark Up - Accessibility, Standardity, SEO, HTML5, Semantic
- Css - CSS3, CSS2, Css/Scss, Response, Adaptive, Cross Browsing( Level >= ie7 ), Grid layout, Flex, Box model, Position, Float, BEM, Animation, ,Css Module,
- Scss Stack : Function, If, Mixin, Mapping, Nest, Anpercent, Variable, inShap, Scope, extend, import, flow controls, Flag, iter
- Nodejs - gulp, lodash, passport, https, express, redis, axios, unirest, multer, react(part), express-session, cashing, crawroling, Meth.js, firebase, mysql, NODE_ENV, async, promise, xss, runscript, babel, i18n, uuid, bcrypt, helmet, os, axios, kill-port, morgan, node-cron, nodemailer, cookie-session, better-npm-run, env preset, winston, logger, npm script, axios, promise, babel, http, helmet, node-cron, nodemailer, os, utf8, async,  ...
- Bundler - Gulp, Webpack, Npm, Yarn
- FrameWork - Express, Bootstrab
- library -  Semantic UI, JQuery, Many Graph Charts,
- Javascript - ES6, ES7, ES8, DOM API, Event Loop, Anysn Await, Promise, None-blocking I/O, Http Shadow, Browswer Workd, Prototype, Cluster, cors, Https, Ajax, Axios, Xss, Amp, common js, GraphQL, Single Thread, Rest API, Restful API, eslint, prettier, npm script, taskrunner, Pattern( module, factory ... 
- Crontab, Linux Scheduling

- Communication - Slack, Confluence, Postman, Zira, Github ( Project, hooking, issue, Mileston ), Flow, Figma, Skitch, Google spreadsheets, Sourcetree, Google Analytics, Todolist, Markdown MD, MD Documentation

**USE FUNCTION.**

+ 게시판 서치기능 개발, 
+ 게시판 페이지네이션 기능 개발, 
+ 게시판 상세페이지 기능개발, 
+ 게시판 소팅 기능개발, 
+ 그래프 방문자 수 기능 개발, 
+ 그래프 방문 통계 기능개발, 
+ 그래프 활동 시간 기능 개발, 
+ 그래프 머문 api 기능개발, 
+ 채팅 기능 개발, 
+ QA 기능 개발, 
+ 블록체인 연계 Graplql 기능개발, 
+ 거래소 기능개발, 
+ 거래소 api 연동 기능 개발,
+ 투자 수익율 기능 개발, 
+ 비밀번호 변경 기능개발, 
+ 임시 비밀번호 발급 기능 개발
+ 메일 전송 기능 개발, 
+ 회원가입 기능 개발, 
+ 회원가입 암호 난독화 기능 개발, 
+ 소설 로그인 기능 개발, 
+ 자체 터미널 기능 개발, 
+ 히스토리 기능 개발, 
+ 로그인, 트렌젝션, 
+ 공헌 히스토리 기능 개발,
+ 다중소팅 기능 개발

<br>

<br>

### 1. 블루팬넷, 개발팀, 2017.08.18 ~ 2018.04.01, 사원, 프론트개발

![cap](https://user-images.githubusercontent.com/25717616/54812195-e37ae700-4ccd-11e9-8e69-2a695379c553.png)




**BUILT WITH**
Express, MySQL, Nodejs, Gulp, AWS로 개발하였습니다.

**CONCEPT**
홈페이지, 대쉬보드에 들어가는 모든 기능을 담아보려고 노력했습니다.

**WEBSITE**

[REMIIT Project 바로가기](https://remiit.io/)

**USE STACK**

+ Server - AWS, Ubuntu, Node.js, Pm2

- CM - Git, Github, Gitlab, Bitbucket
- Mark Up - Accessibility, Standardity, SEO, HTML5, Semantic
- Css - CSS3, CSS2, Css/Scss, Response, Adaptive, Cross Browsing( Level >= ie7 ), Grid layout, Flex, Box model, Position, Float, BEM, Animation, ,Css Module,
- Scss Stack : Function, If, Mixin, Mapping, Nest, Anpercent, Variable, inShap, Scope, extend, import, flow controls, Flag, iter
- Nodejs - unirest, passport, xss, i18n, dotenv, session, cookie, logger, path, router, pattern ...,
- Mysql
- Bundler - Gulp, Webpack, Npm
- FrameWork - Express, Bootstrab
- library - React, Semantic UI, JQuery, Many Graph Charts,
- Javascript - ES6, ES7, ES8, DOM API, Event Loop, Anysn Await, Promise, None-blocking I/O, Http Shadow, Browswer Workd, Prototype, Cluster, cors, Https, Ajax, Axios, Xss, Amp, common js, GraphQL, Single Thread, Rest API, Restful API, eslint, prettier, npm script, taskrunner, Pattern( module, factory ... 
- Communication - Slack, Confluence, Postman, Zira, Github ( Project, hooking, issue, Mileston ), Flow, Figma, Skitch, Google spreadsheets, Sourcetree, Google Analytics, Todolist, Markdown MD, MD Documentation

**USE FUNCTION.**

**클라이언트 홈페이지**

- 메인 페이지 퍼블리싱
- 메인 페이지 최신 뉴스 기능 프론트개발

- 대쉬보드 이벤트 페이지 프론트 개발

- 이벤트 등록, 지갑 연동 프론트 개발

- 이벤트 펜딩상태, 완료 기능 프론트 개발

- 비밀번호 변경 프론트 개발

- 로그인, 회원가입, 비밀번호 리셋 프론트 개발

- 게시판 프론트개발

- 게시판 서치기능 프론트개발

- 게시판 페이지네이션 기능 프론트 개발

- 게시판 소팅 기능 프론트 개발

- 비밀번호 변경 메일 퍼블리싱

- 회원가입 축하 메일 퍼블리싱

+ 모든 페이지 반응형 개발



**어드민 대쉬보드**

- 대쉬보드 그래프큐엘 블록체인 API 프론트엔드 개발
- 게시판 서치기능 프론트 개발 
- 게시판 페이지네이션 기능  프론트 개발
- 게시판 상세페이지 기능 프론트 개발
- 게시판 소팅 기능 프론트 개발
- 회원 상세페이지 프론트 개발
- 회원 컴플레인 티켓 발송 프론트 개발
- 이벤트 타입 등록/편집 기능 프론트 개발
- 이벤트 공지 팝업 기능 프론트 개발
- 그래프 방문자 수 기능 프론트 개발
- 그래프 방문 통계 기능 프론트 개발
- 그래프 활동 시간 기능 프론트 개발
- 그래프 머문 api 기능 프론트 개발
- 웹소켓 채팅 기능 프론트 개발
- FAQ 기능 프론트 개발
- 블록체인 연계 Graplql 기능 프론트 개발 
- 거래소 기능 프론트 개발
- 거래소 api 연동 기능 프론트 개발
- 투자 수익율 기능 프론트 개발
- 비밀번호 변경 기능 프론트 개발
- 메일 전송 기능 프론트 개발
- 회원가입 기능 프론트 개발
- 회원가입 암호 난독화 기능 개발 프론트 개발
- 소설 로그인 기능 프론트 개발
- 자체 터미널 기능 프론트 개발
- 히스토리 기능 프론트 개발
- 로그인, 트렌젝션 프론트 개발
- 공헌 히스토리 기능 프론트 개발
- 다중소팅 기능 프론트 개발



**PROJECT SUMMARY.**

4. ***Remiit***

+ Nodejs 미들웨어, 퍼블리싱과 프론트단 작업을 진행하였으며, Node js 를 이용한 데이터 송수신을 자바 개발자와 하였습니다. 미들웨어로 프레임워크로는 Express를 사용하였으며, Restfull API을 진행하여 Router로 템플릿 엔진 ejs에 뷰를 떨어드려 주었습니다. GraphQL, axios, Unirest를 이용한 데이터를 서버 api로 전송하였고, Postman을 이용하여 데이터 시각화와, 진행되지 않은 서버단 api는 루시드차트이 스키마정의를 통해 미리 라우터를 만들어 놓는 방식으로 실무가 이루어졌습니다. UX팀과의 협업에선 피그마를 이용하여 디자인시안과 회의를 진행하였으며, 디자인 시안이 나오면 퍼블리싱을 진행하고, 퍼블리싱을 진행하면서 동시에 백엔드 개발자분과 Git과 Github으로 커뮤니케이션하여 프론트단 작업을 진행하였습니다. 마케팅 팀에서 flow로 요구 사항이 들어오면 slack으로 PR분이나 CTO과 협의를 하였으며, 회의 결과를 컨플루언스에 업로드 하고 타직군과 스케쥴을 협의하며 작업을 진행하였습니다. 해당 프로젝트의 주요 타게팅은 해외 투자자들을 상대로 진행되어 크로스브라우징은 크롬버전으로 리커버리지를 진행하였으며, i18n을 이용하여 마이페이지 다국어 지원을 진행하였습니다. 총 3개의 서버인 Java서버, web3서버, node.js를 연결하여 블록체인 위에서 동작하는 스테이블한 통신작업과 웹프론트엔드 를 담당하였으며, Nodejs서버 쪽으로는 xss, 소셜 로그인, passport, 난독화, 암호화, env 등을 사용하였으며 aws에 Git 을 물려 aws 리눅스서버로 직접 풀을 받아 배포를 진행하였습니다. 이미지 파일 전송시 multer를 이용하여 aws s3에 업로드 하는 방식을 택하여 사용 하였으며, 모든 페이지는 반응형으로 제작히였고, 싱글 스레드인 자바스크립트를 보다 잘 활용하기위해 논블락킹, 이벤트루프, 테스트큐를 이용하여 코드를 작성하였으며, 노드에서는 부하룰 줄이기 위해 클러스트를 사용하였고, 임시로 저장 할 데이터는 세션 스토리지를 이용하여 부하를 최소화 하였습니다. 작은 프로젝트에는 gulp를 이용하여 es6 ~ es8문법을 사용하여 코딩된 코드를 트랜스 파일 했으며, 스타일시트로는 scss를 사용하고 있습니다. 최소한의 xss를 방어할땐 노드단에서 모듈을 사용하여 막았으며, 유니코드로 전송된 데이터를 다시 스트링 파싱하여 데이터베이스에 저장하고 렌더링할떄 다시 파싱하여 떨궈주는식으로 작업을 하였습니다. 프로젝트의 예정상 리액트 위에서 그래프 큐엘을 아폴로와 사용하려 했으나, 회사 기획상 express 위에서 그래프 큐엘을 데이터 통신까지 성공한 상황입니다. 또한 어드민단 작업도 진행하였으며, 퍼블리싱은 자체적으로 진행하고, 루시드 차트의 요구사항에 맞춰 작업을 진행하였습니다. 어드민단에선 수많은 데이터들을 다뤄야 했고, 백엔드단의 범용성을 높이기 위해 raw한 데이터들을 받아 모두 2차 가공을 프론트에서 진행하였습니다. 송금관련 데이터이다보니 숫자가 많고 수식이 많아 서버단에서 가공을 하기엔 트렌젝션이 많이 발생해 코스트와 부하부분에서 문제가 발생한다고 판단하여 대부분의 데이터를 프론트에서 가공을 하였습니다.  



