## 프로젝트 주제
현실 세계의 소매상을 가상공간에 구현한 인터넷 쇼핑몰을 구축하는 커머스 프로젝트

## 비즈니스 요구사항과 설계
* 데이터베이스
  * 모든 데이터는 로컬 메모리 DB를 구축할 수 있고 외부 DB와도 연동할 수 있다. (미확정)
* 회원
  * 회원 가입을 할 수 있다.
  * 회원은 일반 회원과 셀러 두 가지 등급이 있다.
* 로그인
  * 회원 가입된 계정에 로그인하고 로그아웃 할 수 있다.
  * 로그인 시 회원 가입한적 없는 이메일을 이용하여 로그인을 시도하면 에러가 발생한다.
  * 로그인 시 비밀번호가 일치하지 않는다면 에러가 발생한다.
* 상품
  * 셀러는 상품을 등록 및 삭제할 수 있다.
* 상품 검색
  * 로그인 여부와 상관없이 상품을 검색할 수 있다.
* 장바구니
  * 로그인한 유저는 상품을 장바구니에 담을 수 있다.
  * 로그인한 유저는 자신의 장바구니를 조회할 수 있다.
  * 로그인한 유저는 상품을 장바구니에서 삭제할 수 있다.
* 상품 주문
  * 로그인한 유저는 상품을 주문할 수 있다.
  * 로그인한 유저는 상품 주문을 취소할 수 있다.
  * 상품 주문 시 쿠폰을 사용할 수 있다.
* 쿠폰
  * 셀러는 본인의 상품에 해당하는 쿠폰을 발행할 수 있다.
* 타임딜
  * 셀러는 상품에 타임딜 할인을 적용할 수 있다.
  * 셀러는 상품에 타임딜 할인 적용을 취소할 수 있다.
  
## 도메인

### 회원 도메인 협력 관계
![memberdomain](https://user-images.githubusercontent.com/56020202/210162926-6c67ee9f-8bc5-4c4b-9475-e96df3793685.svg)

### 상품 검색 도메인
![productdomain](https://user-images.githubusercontent.com/56020202/210162998-0e4a10a9-4cd1-429d-8b40-8aa62b366f5d.svg)

### 주문 도메인
![orderdomain](https://user-images.githubusercontent.com/56020202/210163000-b7203739-1e37-4a63-acdd-141550dddee2.svg)

### 장바구니 도메인
![basketdomain](https://user-images.githubusercontent.com/56020202/210162995-e8ae7fa2-96ee-472e-9abe-eb32becdb844.svg)

## 클래스 다이어그램
지속적으로 프로젝트 진행하면서 작성해나갈 예정

## ERD
![commerce](https://user-images.githubusercontent.com/56020202/210163075-4f0eaaf3-c247-4927-be71-6439e341bca9.png)

## 프로젝트 구조
![structure](https://user-images.githubusercontent.com/56020202/210162951-836ff4f9-d321-44b0-ba87-681c7acdd2c5.svg)

## 사용 기술 스택
* Spring Boot `2.5.4`
* Java `11`
* H2 Database
* MariaDB `10.11.0`
* Spring Data JPA

## 주차별 개발 계획

|주차|기능|상태|
|------|---|---|
|1주차|요구사항 정의, 설계 및 프로젝트 셋업|Done|
|2주차|-|Not Started|
|3주차|-|Not Started|
