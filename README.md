## 어플리케이션 소개
대학생들 간에 책, 학용품, 잡화 등을 쉽게 거래하게 도와주는 어플리케이션입니다.
![AppIcon](https://user-images.githubusercontent.com/42515875/53171283-ac111000-3625-11e9-9f90-8b4b7f903a85.png)
![splash](https://user-images.githubusercontent.com/42515875/53171290-b16e5a80-3625-11e9-8a64-e240b1571a3c.png)
## 주요기능.
![appexplain1](https://user-images.githubusercontent.com/42515875/53302125-48dde280-389e-11e9-8f90-64de90a71fd2.png)
![appexplain2](https://user-images.githubusercontent.com/42515875/53854260-19e90e80-400c-11e9-8fba-35652e4ff6cd.png)
![appexplain3](https://user-images.githubusercontent.com/42515875/53854278-2e2d0b80-400c-11e9-88fa-268fb220dae9.png)
![appexplain4](https://user-images.githubusercontent.com/42515875/53302148-8e021480-389e-11e9-9dee-96fe4e462856.png)
### 1. 로그인(O)
### 2. 회원가입
  0. 회원가입 완료되고나서 finish()가 바로 실행되는 거 해결.
  1. 입력값 제한 만들기
	0) 학번입력 - 중복 학번으로 가입 방지.(O)  <br>
	1) 학번입력 - 9자리로 고정.(O)<br>
	2) 학번입력 - 숫자만 입력.(O)<br>
	3) 학번입력 - 앞에 4자리가 2011~2019까지로 제한.(O) <br>
	4) 이름입력 - 한글만 입력.(O)<br>
	5) 이름입력 - 5자리로 제한.(O)<br>
	6) 비밀번호 - 비밀번호, 비밀번호 확인 일치 여부 확인 -> 비동기 방식으로 만들기( )<br>
	7) 전화번호 - 유효성 검사(O)<br>
	7) 전화번호 - 전화번호 인증 가능??<br>
	8) spinner - 학과 종류 더 넣기.<br>
	9) 카메라로 바코드 스캔, 책이름으로 검색하기
	10) 학교인 인증 : 위치정보 받아서 학교인 인증
### 글쓰기
	1) 책 바코드 zxing 기능 추가(O) - 19/01/09
	2) 글쓰기 카테고리(1/2) layout 완성(O) - 19/01/09
	3) 네이버 검색 API 연동 책정보 반환 값 출력() - 19/01/10
	3) 글쓰기 (2/2) layout 완성() - 19/01/10
	4) 입력한 값 데이터베이스에 저장() - 19/01/10
### 글 읽기
	1) 글읽기 UI만들기 () -- 19/01/11
	2) 데이터베이스에서 정보글 가져와서 보여주기 () - 19/01/11
### 카테고리

### main화면
	1) 데이터베이스에서 RecyclerView로 띄우기() - 19/01/10
	2) item 클릭하면 글 읽기로 넘어가게 하기() -- 19/01/11
### 쪽지보내기
-socket, firebase 등으로 구현하려 했으나 실패함.
### 검색창	
