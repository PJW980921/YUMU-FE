# YUMU - 라이브 커머스 웹 사이트

<image src="https://github.com/Team-YUMU/YUMU-FE/assets/124119421/89acb350-70df-4ce1-9ee7-a98dd4a02d53"/>

## 👨🏻‍💻 소개 및 사이트 링크
    아마추어 예술가들은 처리가 곤란한 자신의 작품을 경매로 선보여 뒷처리와 금전,
    자기 어필의 기회를 얻고 일반 사용자들은 마음에 드는 작품을 비교적 저렴한 가격에 구매할 수 있는 기회를 얻는 웹 서비스입니다.



🔗 <a href="https://yu-mu.vercel.app/" target="_blank">YUMU Demo Site Link</a>

🔗 <a href="https://www.figma.com/file/bhKgwf7PVFMytzo65XVyse/%EC%9C%A0%EB%AC%B4-%EB%94%94%EC%9E%90%EC%9D%B8?type=design&node-id=257-547&mode=design&t=pty5KUz8BTXv5IxK-0" target="_blank">YUMU Figma Link</a>

🔗 <a href="http://43.200.219.117:8080/swagger-ui/index.html#/" target="_blank">YUMU Swagger</a>

# 📆 프로젝트 기간
## 2024/02/29 ~ 2024/04/05

# 🛠️ 기술 스택 
<div class="display:flex; gap:5px;">

<div>
    
## ⚙️ Front-End

### FrameWorks
  
<img src="https://img.shields.io/badge/Typescript-3178c6?style=for-the-badge&logo=Typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white">
         
  
### Libraries

  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcn/ui&logoColor=white">
  <img src="https://img.shields.io/badge/reacthookform-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white">
  <img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white">
  <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  
### Lints

  <img src="https://img.shields.io/badge/esLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
<img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">
  
### style

<img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"/>

### env

<img src="https://img.shields.io/badge/dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=white"/> 

### OAuth 2.0

<img src="https://img.shields.io/badge/kakaotalk-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=white">
</div>

<div>
    
## ⚙️ Back-End 

<img src="https://img.shields.io/badge/JAVA 17-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/websocket-F8DC75?style=for-the-badge&logo=websocket&logoColor=white">
<img src="https://img.shields.io/badge/stomp-232F3E?style=for-the-badge&logo=stomp &logoColor=white">

### DB

<img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">


### DevOps

<img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
<img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
<img src="https://img.shields.io/badge/githubactions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  </div>
  <div>
      
## 🖼️ Designer
  
 <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
  </div>
  </div>

<br>

# 🏁 설치 및 시작하기

```
$npm i && npm run dev 이 후 http://localhost:3000/ 접속
```

<hr>

# 🎯 담당 페이지 - 내정보(/mypage) 및 기여 부분
- 디렉토리 구조 및 axios/API 통합을 포함한 초기 프로젝트 설정 확립
- CORS 정책 우회 및 토큰관리
- React-hook-form을 활용한 Input 및 zod를 활용한 정규식 적용 에러메세지 공통 컴포넌트 생성
- YUMU 마이페이지 UI/UX 구현
- shadcn/ui 및 Tailwind 사용자 정의를 사용하여 스타일이 지정된 공통 구성 요소
- 사용자 경험 최적화를 위한 마이페이지 및 헤더 컴포넌트에 tanstack-query 적용
  - 마이페이지 수정 시 헤더의 닉네임 및 프로필 이미지가 즉시 업데이트되도록 설정
  - 낙찰/판매/관심 목록 query를 활용한 무한스크롤 구현
        - 데이터패칭중일때shadcn/uispinner 컴포넌트활용
- 팀 프로젝트 작업 진행 중 공통적인 tailwind className을 위한 prettier,eslint rule 적용
    - rule 지키지 않을 시 husky lint-staged 를 통해 배포 금지
## 협업관련
- 디자이너/백엔드와 지속적인 소통을 통한 의사소통 경험 역량 향상
- 프로젝트 진행 중 깔끔한 branch 관리를 위한 squash&merge 활용


# 📦 Directory 구조 
```
📦src
 ┣ 📂components
 ┃ ┣ 📂common
 ┃ ┣ 📂domain
 ┃ ┃ ┣ 📂landing
 ┃ ┃ ┣ 📂myPage
 ┃ ┃ ┃ ┗ 📂Tabs
 ┃ ┃ ┃ ┃ ┣ 📂Edit
 ┃ ┃ ┗ 📂search
 ┃ ┣ 📂svgs
 ┃ ┗ 📂ui
 ┣ 📂contexts
 ┣ 📂lib
 ┣ 📂pages
 ┃ ┣ 📂auction
 ┃ ┃ ┗ 📂[auctionid]
 ┃ ┃ ┃ ┣ 📂detail
 ┃ ┃ ┃ ┣ 📂live
 ┃ ┃ ┃ ┗ 📂streaming
 ┃ ┣ 📂callback
 ┃ ┣ 📂chatting
 ┃ ┣ 📂detail
 ┃ ┣ 📂landing
 ┃ ┣ 📂mypage
 ┃ ┣ 📂registration
 ┃ ┣ 📂search
 ┃ ┣ 📂signin
 ┃ ┣ 📂signup
 ┣ 📂services
 ┣ 📂styles
 ┣ 📂types
 ┃ ┣ 📂validator
```

