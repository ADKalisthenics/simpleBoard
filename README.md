# simpleBoard
A very simple board project which go back to the basic

## 개발 환경
> CSR 환경으로 프론트와 백서버 분리
- BackEnd
    - Spring Boot
- FrontEnd
    - VueJS
- DBMS
  - MYSQL(Docker 사용)
- TOOL : 각자 편한 것 사용

## 설계
> 게시판, 게시글 조회/수정/삭제, 파일 업로드, 회원가입, 로그인 기능만 구현
- 예시 Page
  - [게시판](./docs/blueprint/board.html)
  - [회원가입](./docs/blueprint/join.html)
  - [로그인](./docs/blueprint/sign_in.html)
  - [게시글](./docs/blueprint/read_post.html)
  - [게시글 작성](./docs/blueprint/write_post.html)
  - [게시글 수정](./docs/blueprint/update_post.html)

- ERD
    - user(사용자), post(게시글), file_info(파일정보) 3개의 table 설계
  ![ERD 이미지](./docs/imgs/ERD.drawio.png)

### RULES
- Naming Rule : camelCase 사용
- return message [LINK]
- File 저장 규칙 [LINK]
- API 작성 규칙 : RESTFUL [LINK](https://learn.microsoft.com/ko-kr/azure/architecture/best-practices/api-design)