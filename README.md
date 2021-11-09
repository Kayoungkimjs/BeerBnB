# Beerbnb 🍻
### 술은 마셔보고, 여행은 떠나보는거야! 주종에 따라 술 마시기 좋은 최적의 숙소를 찾아드립니다.
![스크린샷 2021-11-01 오후 8 23 35](https://user-images.githubusercontent.com/83155239/139664694-135198c8-1c75-4cb8-b4fb-05fb8a7ddfb4.png)
---
## ⚒ 주요 기술 스택 
<img alt="JavaScript" src ="https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white"/>   <img alt="ReactJS" src ="https://img.shields.io/badge/React-61DAFB.svg?&style=for-the-badge&logo=React&logoColor=white"/>   <img alt="ReactRouter" src ="https://img.shields.io/badge/React Router-CA4245.svg?&style=for-the-badge&logo=React Router&logoColor=white"/>   <img alt="Sass" src ="https://img.shields.io/badge/Sass-CC6699.svg?&style=for-the-badge&logo=Sass&logoColor=white"/>   <img alt="JSON" src ="https://img.shields.io/badge/JSON-000000.svg?&style=for-the-badge&logo=JSON&logoColor=white"/>

## 기타 
- Common : AWS(RDS/EC2), RESTful API, react-kakao-login
- Communication: Slack, Trello, Goolge Docs

#### 개발은 초기 세팅부터 전부 직접 구현했으며, 백엔드 서버와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발했습니다.
---
# 구현 사항
## 📌 카카오 소셜 로그인
![로그인](https://user-images.githubusercontent.com/83155239/139666738-738a8aec-d944-421e-bd01-1d94a62656b1.gif)
- 카카오 API를 활용해 소셜 로그인 기능을 구현했습니다.
- API fetch 후 token 정보를 백엔드 서버에 전송, 해당 페이지 접속 권한이 있는 token을 받아오는 일련의 과정을 실행합니다.
- 숙소 예약/등록시 필요한 정보(이름, 프로필 사진, 생년월일)를 받아옵니다.
## 📌 호스트 등록을 위한 주소 검색 및 등록
![주소등록](https://user-images.githubusercontent.com/83155239/139666746-82961f2f-fbfc-48f4-84ba-b80f5160855d.gif)
- 카카오 로컬 API, axios 라이브러리를 활용해 주소 검색 및 등록 기능을 구현했습니다.
## 📌 호스트 등록을 위한 정보 등록
- 숙소 등록에 필요한 다양한 form tag를 구현했습니다. 
- 사진, 인원(증감 버튼), 금액 등 유저 데이터를 입력 후 저장하면 '예약 페이지'에 업로드됩니다.

# ⚙️ 실행 방법
1. git repository clone 및 npm install <br />

`git clone https://github.com/Kayoungkimjs/BeerBnB.git` <br />
`npm install`

2. React App 열기 <br />
`npm start` 
---
## 개발 인원 및 기간
- 개발기간 : 2021/8/16 ~ 2021/8/27
- 개발인원 : 프론트엔드 4명 백엔드 2명

## Reference
- 이 프로젝트는 '에어비앤비(AirBnb)' 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

