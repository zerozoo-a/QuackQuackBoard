# QuackQuackBoard

## Quack Quack Board ReadMe에 오신것을 환영합니다!

해당 repository는 github pages 서버에 업로드하기 위해 제작되었습니다.
webpack을 통해 optimization을 거치면서 uglify 되어 코드를 읽기 난해합니다. 
따라서 코드를 보고 싶으시다면 아래의 링크를 클릭해 이동해주시길 바랍니다.

[zerozoo-front/myBoard](https://github.com/zerozoo-front/myBoard)

---

### feature
---

 본 사이트는 google firestore를 활용해 OAuth 인증과 실시간 데이터베이스 연동을 통해
 채팅하듯이 유저의 데이터 입력에 따라 바로 화면이 갱신되는 게시판을 가지고 있습니다.
 기본적인 CRUD 기능을 내장하고 있습니다.
 
 또한 backend와 연동하여 자신의 게시글을 모아보거나 닉네임, 유저 프로필 사진을 변경할 수 있습니다.
 
 
 ### HOME
 ---
 
![homegif](https://user-images.githubusercontent.com/80259925/122519279-3ed2e580-d04d-11eb-8190-57bafc990267.gif)

Home 화면은 사이트의 주된 기능인 다른 유저의 실시간 게시글을 확인할 수 있고
자신도 게시글을 업로드 할 수 있는 곳입니다.

- 게시글은 가장 최신 글이 최상단에 배치되고 이전 글들은 점점 밑으로 내려가게 정렬되었습니다.

- 유저의 이미지는 클릭할 경우 최대사이즈로 화면에 표시되고 다시 클릭 할 경우 사라지게 됩니다.

- 자신의 게시글이 아닌 경우 편집, 삭제가 가능합니다. 자신의 게시글이 아닌 경우 편집, 삭제가 불가능합니다.


---

### USER INFO

---
![userinfoChange](https://user-images.githubusercontent.com/80259925/122522497-fddcd000-d050-11eb-9457-085e8d6db134.gif)

- 유저의 개인정보를 변경할 수 있습니다.

- 유저가 작성한 게시글만 따로 모아 볼 수 있습니다.

---




