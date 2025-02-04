# board
<div align="center">
  <p align="center">
    <img src="../toys-images/board/시연이미지1.png" align="center" width="35%">
    <img src="../toys-images/board/시연이미지4.png" align="center" width="35%">
  </p>
  <p align="center">
    <img src="../toys-images/board/시연이미지3.png" align="center" width="35%">
    <img src="../toys-images/board/시연이미지2.png" align="center" width="35%">
  </p>
</div>
<div align=center>
    <h3>
        🌐 시연영상
         <a href="https://www.youtube.com/watch?v=b2JAx2kzs_g">유튜브링크</a>
    </h3>
</div>

<br>

## 👨🏻‍🏫 프로젝트 소개

<details>
<summary><b> 📌 프로젝트 개요</b></summary>
<br>

- 패스워드 인증기반 글(작성, 수정, 삭제, 조회), 댓글(작성, 삭제)을 가진 게시판 서비스 앱
- NodeJs, Express, MongoDB, 템플릿엔진인 express-handlebars를 사용해 게시판 서비스 앱 구축

</details>

<br>

<details>
<summary><b> 🏃 프로젝트 실행</b></summary>
<br>

```bash
# prerequisites: npm, node, mongodb(docker)
# execution
docker-compose up -d
git clone https://github.com/mpqm/board.git
npm install
npm start
```

</details>

<br>

<details>
<summary><b> 🚀 주요 기능 설명</b></summary>
<br>

- 게시글
    - 게시글 작성시 비밀번호 해쉬 처리후 DB저장
    - 게시글 상세보기를 통해 게시물 정보(댓글, 작성자, 작성일자 등)확인
    - 게시글 수정, 삭제시 check-pasword API 을 통해 비인가적인 삭제 호출 막음
- 댓글
    - DB의 Post에 배열 형식으로 Post DB에 존재 
    - 댓글 작성시 비밀번호 해쉬 처리후 Post DB destruct 후 저장
    - 댓글 삭제시 2중 쿼리사용 API를 통해 비밀번호 인증후 삭제
- 메인 리스트
    - 리스트에서 게시글 목록, 검색, 페이지 네이션
    - 페이지네이션구현 -> utils/paginator.js 참조

</details>

<br>

<details>
<summary><b> 💻 기술 스택</b></summary>
<br>

| **Category** |**Skills**| 
|-------------|---------|
|**Language**| ![HTML5](https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) |
|**Frontend**| ![Handlebars.js](https://img.shields.io/badge/handlebars.js-3776AB?style=for-the-badge&logo=Handlebars.js&logoColor=white) |
|**Backend**| ![express](https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white)  |
| **Database**| ![MongoDB](https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white)|
| **Env**|![npm](https://img.shields.io/badge/npm-D24939?style=for-the-badge&logo=npm&logoColor=white) ![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) 

</details>