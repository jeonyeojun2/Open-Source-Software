![header](https://capsule-render.vercel.app/api?type=rect&height=300&color=gradient&text=Open%20Source%20Software-nl-Term%20Project&textBg=false&fontSize=50&fontAlign=50)
## 23102466 전여준
# 목차
- [회원관리](#회원-관리)
- [AI를 활용한 리뷰 신뢰도 평가](#AI를-활용한-리뷰-신뢰도-평가)

<hr/>
  
# 1. 회원관리
### 🛠 기술스택
#### 백엔드
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/json%20web%20tokens-%23000000.svg?&style=for-the-badge&logo=json%20web%20tokens&logoColor=white" /> <img src="https://img.shields.io/badge/java-%23007396.svg?&style=for-the-badge&logo=java&logoColor=white" /> <img src="https://img.shields.io/badge/mysql-%234479A1.svg?&style=for-the-badge&logo=mysql&logoColor=white" />
#### 프론트엔드
<img src="https://img.shields.io/badge/react-%2361DAFB.svg?&style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/typescript-%233178C6.svg?&style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">

<hr/>

### 🛠 구조

<hr/>

### 🚀 기능
#### 😃 로그인
- 아이디와 비밀번호를 올바르게 입력하면 로그인할 수 있다
- 카카오, 네이버 로그인을 통해 간편하게 로그인할 수 있다
#### 😃 회원가입
- 아이디 중복확인을 통해 같은 아이디를 만들 수 없도록 한다
- 비밀번호 일치를 확인한다
- 이메일 인증을 한다
  

# 2. AI를 활용한 리뷰 신뢰도 평가
### 🛠 기술스택
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/openai-%23412991.svg?&style=for-the-badge&logo=openai&logoColor=white" />
### 🛠 구조
### 🚀 기능
#### 😃 크롤링
- 네이버 리뷰, 쿠팡 리뷰를 크롤링해 데이터베이스를 만든다
- OpenAI api를 사용해 리뷰의 신뢰성을 판단한다
- 각 리뷰의 신뢰도를 5점 만점으로 평가한다
