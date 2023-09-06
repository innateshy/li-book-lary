# Spring Project - li-book-lary
스프링으로 구현한 온라인 서점 사이트

## 🏟 프로젝트 소개
교보문고 등을 참고한 온라인 서점 사이트입니다.
<br>

## ⏲ 개발 기간
* 2023.07.17일 ~ 2023.08.02일
* 2023.08.21일 ~ 2023.09.04일 (기능 및 데이터 시각화 추가)
 
### 👨‍💻 멤버 구성
- 조장 양상민 - 도서 검색, 도서 목록 및 상세 페이지, 장바구니(CRUD), PPT 제작, Database 설계
- 조원1 박지애 - 회원가입/로그인, 마이페이지, 아이디, 비밀번호 찾기(이메일 발송) 
- 조원2 정준엽 - header&footer, Database 설계, 결제 및 환불 API, 문의 게시판(CRUD, 페이징, 답글), 통계(R)
- 조원3 지우림 - 신간 등록, 카테고리 목록 및 등록, 사용자 주문목록, 배송조회 API, 관리자 페이지(회원관리, 배송관리)
- 조원4 최진규 - 관리자 재고 페이지(정렬, 검색, 재고수정), 회사소개(지도 API)

### 🛠 개발 환경
- 'Java 11' <img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/>
- 'JDK 11.0.18'
- **IDE** : sts 3.9.18 <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
- **Database** : Oracle DB(18c) <img src="https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white"/>
- **Server** : Tomcat 8.5 <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black"/>

### 🔨 사용 기술
HTML <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
CSS <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
JavaScript<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
jQuery<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>
mybatis
R <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=R&logoColor=white">
</br>

## 📌 주요 기능
#### 회원가입
- ID 중복 체크(Ajax) 

#### 로그인
- DB값 검증
- ID 찾기, PW 찾기 (이메일 발송)
- 로그인 시 세션(Session) 생성 및 인터셉터 호출

#### 마이 페이지
- 내 정보 수정
- 회원 탈퇴
- 예약정보 확인, 취소
  
#### 메인 페이지
- 지도 UI
- 카테고리 검색(Ajax), 검색어 검색, 추천도서

#### 도서목록, 상세페이지
- 즉시 구매, 장바구니 담기 선택
- 도서 정보
- 
#### 장바구니
- 장바구니 수량 조정(Ajax)
- 장바구니 선택 항목 삭제, 전체 삭제 기능(Ajax)

#### 결제
- 추가 수량 및 포인트 선택(Ajax)
- 배송 선택
- 결제 API (포트원, Ajax)

#### 사용자 주문 목록
- 구매확정, 환불(포트원, Ajax)
- 배송조회 API
  
#### 문의 게시판
- 리뷰작성, 게시판 목록, 읽기, 수정, 삭제(CRUD)
- 게시판 목록 페이징
- 관리자 답글 기능

#### 카테고리 페이지
- 카테고리 등록(Ajax)
- 카테고리 목록

#### 신간 등록
- 파일 업로드
- ISBN 유효성 검사(Ajax)

#### 통계 페이지
- 카테고리별 판매량 통계(RJAVA, RJDBC)

#### 회원관리
- 회원 삭제

#### 관리자 주문관리 페이지
- 배송 상태 변경(Ajax, 드롭다운)

#### 재고 관리
- 조건 검색 기능(가격범위, 검색어)
- 정렬
- 재고 수량 조절

#### 회사소개
- 지도 API

## DB 구성
