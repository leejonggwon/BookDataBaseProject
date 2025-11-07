## 서비스소개 
#### 서비스명
▪ 스프링 기반 도서관리시스템(Book Management System)
#### 서비스설명
▪ 본 프로젝트는 스프링(Spring) 프레임워크와 MyBatis 기반으로 개발된 도서관리시스템 웹사이트 입니다. <br>
▪ 도서의 등록, 조회, 수정, 삭제(CRUD) 기능을 제공하며 비동기 통신(AJAX)을 통해 실시간으로 목록을 갱신함으로 사용자 경험을 향상시켰습니다. <br>
▪ 보유 도서를 효율적으로 관리하기 위한 웹 애플리케이션으로 관리자는 JSP 기반의 직관적인 UI를 통해 웹 화면에서 도서 정보를 손쉽게 관리할 수 있도록 하는 것을 목표로 합니다.

<br>

## 개발내용
### 개발환경
▪ 개발 언어: Java (JDK 11 이상) <br>
▪ 프레임워크: Spring Framework 4.x / MyBatis <br>
▪ 데이터베이스: MySQL <br>
▪ 프론트엔드: JSP, jQuery, AJAX, HTML/CSS <br>
▪ 개발도구: eGovFrame 4.0.0, Eclipse, Apache Tomcat 9 <br>

### 주요기능 구성 
#### 1) BookController / BookRestController
▪ BookController: 기본 페이지 이동, JSP 매핑 담당 <br>
▪ BookRestController: AJAX를 통한 비동기 데이터 처리 담당 (JSON 형태로 응답) <br>

#### 2) Mapper + SQL Mapper (MyBatis)
▪ BookMapper.java: 인터페이스 정의 (CRUD 메서드 선언) <br>
▪ BookMapper.xml: 실제 SQL 쿼리 정의 <br>

#### 3) main.jsp (메인 화면)
▪ 도서 목록을 테이블 형태로 표시 <br>
▪ 오른쪽에 [등록], [수정], [삭제] 버튼 제공 <br>
▪ 모든 기능은 비동기 방식(AJAX) 으로 동작 <br>

### 개발 포인트
▪ Spring MVC 패턴을 적용하여 Controller - DAO - Mapper 계층 구조로 설계 <br>
▪ AJAX 비동기 통신을 통해 페이지 새로고침 없이 CRUD 기능 구현 <br>
▪ MyBatis Mapper XML을 활용해 SQL을 명확하게 관리 <br>
▪ JSP + jQuery로 직관적이고 간결한 사용자 UI 제공 <br>

## 기능설명
### 도서조회
<p align="center">
  <img src="https://github.com/user-attachments/assets/8cc643a3-7593-4b01-86e5-0fe48b80f52f" width="500" />
</p>

<br>
<br>

## 메인페이지(공지사항)
<p align="center">
  <img src="https://github.com/user-attachments/assets/7e1e3fa0-74a2-41fd-8e4c-8b4dc35a0aba" width="500" />
</p>

<br>
<br>

## 커뮤니티
<p align="center">
  <img src="https://github.com/user-attachments/assets/282b4579-32ec-4b63-9685-37db1411c2d3" width="500" />
</p>

<br>
<br>

## 게시물등록 기능
<p align="center">
  <img src="https://github.com/user-attachments/assets/5a3d3e14-6361-4042-a353-57f9c0eab9e9" width="500" />
</p>

<br>
<br>



