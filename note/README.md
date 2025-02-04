# note
<div align="center">
    <img  style="width: 50%" src="../toys-images/note/메인 이미지1.png">
</div>
<div align=center>
    <h3>
        🌐 시연영상
         <a href="https://www.youtube.com/watch?v=Wl9k9AdOlCM">유튜브링크</a>
    </h3>
</div>

<br>

## 👨🏻‍🏫 프로젝트 소개
<details>
<summary><b> 📌 프로젝트 개요</b></summary>
<br>

- MognDB Object Id를 통한 개인노트서비스, 세션 인증, express 기반 REST API설계
- React, NodeJs, Express, MongoDB, TypeScript를 사용한 MERN 스택 앱 구축

</details>

<br>

<details>
<summary><b> 🏃 프로젝트 실행</b></summary>
<br>

 ```bash
 # prerequisites: npm, node, MongoDB(docker)
 # execution
 docker-compose up -d
 git clone https://github.com/mpqm/nodejs-service-note.git
 cd backend
 npm install
 npm start
 cd frontend
 npm install
 npm start
 ```

</details>

<br>

<details>
<summary><b> 🚀 주요 기능 설명</b></summary>
<br>

- User 
    - User별 MongoDB Obj ID를 통해 자신만의 NotePage를 가짐
    - 회원가입, 로그인/아웃, DB 저장 세션 인증 구현
    - react-hook을 이용한 커스텀 유효성검증 로그인, 회원가입용 Form 객체 구현
- Note
    - NOTE 삭제, 작성, 수정, 조회
    - MongoDB Object Id를 통해 User ObectId를 기준으로 개인 식별
    - react-bootstrap Modal을 이용한 Note 작성, 수정 컴포넌트 구현

</details>

<br>

<details>
<summary><b> 💻 기술 스택</b></summary>
<br>

| **Category** |**Skills**| 
|-------------|---------|
|**Language**| ![HTML5](https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![typescript](https://img.shields.io/badge/typescript-3178C6.svg?&style=for-the-badge&logo=typescript&logoColor=white) |
|**Frontend**| ![React](https://img.shields.io/badge/React.js-61DAFB.svg?&style=for-the-badge&logo=React&logoColor=white) 
|**Backend**| ![express](https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white)|
| **Database**| ![MongoDB](https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white)|
| **Env**|![npm](https://img.shields.io/badge/npm-D24939?style=for-the-badge&logo=npm&logoColor=white) ![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) 

</details>