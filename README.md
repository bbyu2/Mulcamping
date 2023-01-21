![image](https://user-images.githubusercontent.com/84059211/212462581-317da28e-4ce9-40ec-b364-37c5cf9aeb14.png)
# Mulcamping

# 목차
[1. 개요](#개요)

[2. 개발환경](#개발환경)

[3. 구현화면-사용자](#구현화면-사용자)

[4. 구현화면-관리자](#구현화면-관리자)

<br/>

## 개요
- Open API를 활용하여 보다 편리한 캠핑 장소 검색 및 커뮤니티 사이트 제공
![mc-1](https://user-images.githubusercontent.com/84059211/212459538-1360c50e-3ad8-4e46-88a1-ca7e95957c6f.png)


### 개발 인원 및 기간
- 기간 : 2022-04-25 ~ 2022-05-24 (총 4주)
- 인원 : 6명 (프론트 엔드 3명, 백 엔드 3명)

### 🙌 담당 역할 🙌
- 프론트 엔드 담당으로 메인 페이지 및 전체적인 디자인 및 레이아웃을 메인으로 담당

### 주요 기능
- 무장애 여행 API를 활용하여 관광 약자에게 편안한 여행 정보 제공
- 여행 플래너 작성을 통해 관광코스를 작성하는데 도움을 줌
- 시각장애인의 접근성을 높이기 위한 TTS 기능 활용
- 제주도에서의 관광약자들을 위한 OPEN API기반 여행 정보 소개 웹 어플리케이션 

<br/>

## 개발환경
![mc-2](https://user-images.githubusercontent.com/84059211/212459597-729f4bd4-1dd9-4ba1-86d8-6a5057cf5a74.png)
### 의존성
- jdk 11
- springboot 2.6.6
- mysql 8.0
- apache tomcat 9.0

### 기술 스택
- <b>FrontEnd</b>
    - Html
    - CSS
    - JavaScript, jQuery , Ajax
- <b>BackEnd</b>
    - Java
    - SpringBoot
    - Mybatis
- <b>DB</b>
    - MySQL
- <b>IDE</b>
    - STS
- <b>API TEST</b>
   - POSTMAN
- <b>Coorperation</b>
   - Github
   - Goole Drive
   - AWS
   
### 페이지 흐름도
![mc-3](https://user-images.githubusercontent.com/84059211/212459733-256a0161-4c2d-422c-9a44-589c106e7f7f.png)

### 데이터 베이스
![mc-4](https://user-images.githubusercontent.com/84059211/212459788-3d16f791-1d52-47e3-b770-f8f9b4812c0a.png)

<br/>

## 구현화면-사용자

### 1.Main
```
로그인 및 로그아웃, 캠핑장 찾기, 캠핑 커뮤니티로 이동 가능
```
![mc-5](https://user-images.githubusercontent.com/84059211/212460753-55ed69ea-f301-4caf-9a04-90019fd4a3fd.png)
![mc-6](https://user-images.githubusercontent.com/84059211/212460760-9539cf2b-2ead-49fb-b3b6-785c19b1f09c.png)
![mc-7](https://user-images.githubusercontent.com/84059211/212460767-97e5b6e7-fa3b-40e5-a735-97c64faad517.png)

### 2.Login, SignUp
```
로그인 및 유효성 검사를 통한 회원가입, 아이디 및 패스워드 찾기
```
![mc-9](https://user-images.githubusercontent.com/84059211/212460655-0715de12-200b-4b77-ab2d-19f68c2a3f4a.png)
![mc-8](https://user-images.githubusercontent.com/84059211/212460657-d59e6a9c-c2ee-486d-be00-0fee36bc6977.png)

### 3.My Page
```
일정확인, 회원정보 수정, 참여한 캠핑목록, 개설한 캠핑목록 확인 가능
```
![mc-10](https://user-images.githubusercontent.com/84059211/212460530-f568f760-6c3f-489a-bd14-1654402ce421.png)

### 4.Camping Serch
```
상세 조건검색 및 태그를 통한 캠핑장 검색  
```
![mc-11](https://user-images.githubusercontent.com/84059211/212460874-a1c87f83-f9e7-4011-8607-4196c7c78780.png)

### 4-1.Camping Search detail page
```
전경 이미지, 위치, 연락처, 홈페이지, 소개글등 기본 정보 캠핑장의 기본 정보 확인가능
```
![mc-12](https://user-images.githubusercontent.com/84059211/212460979-fcfd2c70-9bed-4474-9d79-42a5dd40f861.png)
```
모달창을 활용한 후기 작성 및 추천 기능
```
![image](https://user-images.githubusercontent.com/84059211/212462499-be7dba5c-b3de-47cd-bdc1-bef4f46f79c5.png)

### 5. Gather People
```
글 등록, 리스트 확인, 캠핑 참여 및 세부정보 확인등 
```
![mc-14](https://user-images.githubusercontent.com/84059211/212461569-7d9c96fd-1d9f-432b-bcf7-58e4547e163e.png)
![mc-15](https://user-images.githubusercontent.com/84059211/212461570-e7317c50-4206-4bfb-87bc-4975117ede7d.png)

### 7. Camping Supplies
```
캠핑용품 나눔, 구매 및 판패 가능
```
![mc-16](https://user-images.githubusercontent.com/84059211/212461843-b77dad30-57a6-4adb-9dfc-85faf4ea6bd0.png)
![mc-17](https://user-images.githubusercontent.com/84059211/212461844-018b7289-13bc-4079-a01e-27b90fb06975.png)

<br/>

## 구현화면-관리자
### 1. 대시보드
```
회원 목록, 캠핑장 목록, 캠퍼 모집 목록등 회원 및 게시글 통합 관리
```
![image](https://user-images.githubusercontent.com/84059211/212461954-450f7779-753d-4b1f-88cc-39e913da1983.png)
![image](https://user-images.githubusercontent.com/84059211/212462010-1ba068ac-61eb-4633-93b7-9a35d1787b81.png)

<br/><br/><br/>
***

<div align=center>
<h4> 👈 back to main 👈 </h4>
<a href="https://github.com/bbyu2"> 
<img src="https://img.shields.io/endpoint?label=bbyu2&logo=github&style=for-the-badge&url=https%3A%2F%2Fgithub.com%2Fbbyu2%2F"/>
</a>
</div>
