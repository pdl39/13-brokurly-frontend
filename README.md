# Team BroKurly
### Trello
https://trello.com/b/37IIkVmJ/team-brokurly
![](https://images.velog.io/images/kho5420/post/2aeaf7a3-8921-440b-8eba-17437cc8dfaa/image.png)
## :broccoli: 프로젝트 소개
>한국의 신선 식품 전문 온라인 쇼핑몰인 [Market Kurly](https://www.kurly.com/shop/main/index.php)를 클론 하는 프로젝트를 진행했습니다.
**마켓 컬리**는 수도권 한정으로 당일 주문 시 다음 날 새벽 배송되는 샛별배송 배달 서비스를 하고 있습니다.
신선한 식재료를 직접 장보러 가지 않아도 바로 받아서 먹을 수 있다는 장점을 가지고 있고 코로나 사태로 인해 이용자들이 많이 늘어난 사이트이기도 합니다.
## :broccoli: 프로젝트 참가자 (Front + Back)
#### :call_me_hand: Team BroKurly
![](https://images.velog.io/images/kho5420/post/b20eb17f-b0cd-4c53-bc68-9a5820ae5d1a/image.png)
+ 저희는 어떻게 하다보니 남자분들끼리 모이게 되어서 bro + kurly 라는 이름의 `brokurly`라는 이름으로 팀명을 정했습니다.
### :man:‍:man:‍:boy:‍:boy:‍ FrontEnd
+ 강수명
+ 이동훈
+ 허덕형
+ 김제형
### :man:‍:boy:‍ BackEnd
+ 김동현 (PM)
+ 김형욱
## :broccoli: 프로젝트 기간
2020.10. 19 ~ 2020. 10. 30 약 2주간 진행
## :broccoli: 프로젝트 영상
https://www.youtube.com/watch?v=PfhrUruCmWU
## :broccoli: 기술 스택
### :man:‍:man:‍:boy:‍:boy:‍ FrontEnd
+ HTML / CSS
+ JavaScript
+ React(CRA 세팅)
+ React(Router DOM)
+ Sass
+ Redux(ReactRedux, Persist, logger)
+ SweatAlert
+ IMport
### :man:‍:boy:‍ BackEnd
+ Python
+ Django
+ CORS Header
+ Bcrypt
+ PyJWT
+ MySQL
+ REST API
+ Twilio (문자 인증 SMS 서비스)
+ AqeuryTool (데이터베이스 모델링)
+ AWS EC2 서버에 RDS 인스턴스를 연결하여 배포
### :man::wrestling: 협업 도구
+ Slack
+ Git + GitHub
+ Trello를 이용해 일정관리 및 작업 현황 확인
+ Postman (API 관리)
## :broccoli: 구현한 기능
### :man:‍:man:‍:boy:‍:boy:‍ Front End
### 메인페이지
+ 메인배너 및 섹션별 상품 슬라이더 직접 구현
+ MD의 추천 카테고리별 상품 렌더링 구현
+ 사이드메뉴 스크롤링 이벤트 구현
+ 최근 본 상품 구현
### 카테고리별 상품리스트
+ 장바구니 모달창
+ 상품카드 분류 및 정렬
+ 상품 상세페이지 구현
+ 고객후기 게시판 구현
+ 상품 할인 금액 적용
### Navbar
+ 카테고리 상세 메뉴 구현
### 회원가입 & 로그인 (SignUp & SignIn)
+ 회원가입 아이디 / 비밀번호 유효성 검사
+ 필수 사항 / 선택 사항을 분리 구현
+ JWT를 이용한 로그인
+ 아이디 찾기 / 비밀번호 재등록 구현
### 장바구니
+ 상품 최종 금액 및 할인 금액 적용
+ 적립금 적용
### 마이페이지 (마이컬리)
+ 늘 사는 것 (찜목록) 장바구니 등록
+ 적립금 반영
### 주문서
+ Iamport 결제API를 이용하여 결제창 구현
### :man:‍:boy:‍ Back End
### 메인페이지
+ Setion 별 상품 리스트 API
+ MD의 추천 카테고리별 필터링 API
### 카테고리별 상품리스트
+ 카테고리 별 상품 필터링 및 검색 API
### 신상품 & 베스트 페이지
+ 현재 날짜 기준 한 달안에 올라온 상품들만 올려주는 신상품 페이지 API
+ 조회수 기준으로 필터링한 상품만 보여주는 베스트 페이지 API
### 알뜰쇼핑 페이지
+ 할인되는 상품들만 보여주는 알뜰쇼핑 페이지 API
### Navbar
+ 상품 카테고리 API
+ 로그인을 하게 되면 유저의 이름과 회원 등급이 표시
+ 장바구니에 상품을 담았다면 상품의 갯수가 장바구니 아이콘 위에 표시
### 회원가입 & 로그인 (SignUp & SignIn)
+ 회원가입 시 TWILIO 라이브러리를 이용한 휴대폰 인증
+ bcrypt를 사용한 암호화
+ JWT 로그인 구현 및 @decorator를 이용해서 토큰 인증
### 장바구니
+ 상품의 장바구니 등록 (개수 포함)
+ 장바구니 내역 조회
+ 장바구니 상품 수량 변경 및 목록 삭제
### 마이페이지 (마이컬리)
+ 늘 사는 것 (찜목록)
+ 주문 내역
### 주문서
+ 주문하기 할 때 유저정보 가져오기
+ 주문하면 장바구니에 있는 상품들을 주문내역으로
## :broccoli: 프로젝트 진행과정
**Trello**를 이용해서 각자 처음 구현할 기능들을 Backlog에
필요한 이미지들은 Design에
이번주 까지 할 일은 To Do (This Week)
현재 하고 있는 작업들은 Doing
그리고 Front와 Back간의 테스트 중인 부분은 Testing
위의 작업들이 완료되면 Done에 티켓을 작성해서 분류하였습니다.
![](https://images.velog.io/images/kho5420/post/3f8b4322-e82c-4d66-9575-ab16ee9839b2/image.png)
+ 프로젝트가 끝난 시점에서의 Trello
