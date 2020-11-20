### 회원가입

url 

POST/upstory/join

Params

| KEY      | TYPE        | DESCRIPTION                           |
| -------- | ----------- | ------------------------------------- |
| email    | varchar(28) | primary key / 아이디로 설정할 이메일. |
| pw       | varchar(20) | not null                              |
| name     | varchar(8)  | not null                              |
| nickname | varchar(24) | not null                              |
| age      | int         |                                       |
| birth    | datetime    |                                       |

Respon

로그인 화면



### 로그인

url 

POST/upstory/login

Params

| KEY   | TYPE        | DESCRIPTION |
| ----- | ----------- | ----------- |
| email | varchar(28) |             |
| pw    | varchar(20) |             |

Respon

토큰



### 아이디 / 비밀번호 찾기

url

POST/member/find/password

Params

| KEY      | TYPE | DESCRLPTION |
| -------- | ---- | ----------- |
| email    |      |             |
| nickname |      |             |

Respon

pw (이메일과 닉네임 모두 존재할 시) 



url

POST/member/find/id

Params

| KEY      | TYPE | DESCRLPTION |
| -------- | ---- | ----------- |
| pw       |      |             |
| nickname |      |             |

Respon

email



### 회원 탈퇴

url

POST/member/quit

Params

| KEY  | TYPE | DESCRLPTION |
| ---- | ---- | ----------- |
| pw   |      |             |

Respon

회원 탈퇴 페이지



### 계정 관리 페이지

### 1. 내계정

김선정

### 2. 보안

이종은

### 3. 내 블로그

김

### 4. 블로그 폐쇄

### 5. 데이터 관리 (삭제 하기)



### 피드

### 1. 구독중, 구독자 관련



### 스토리 (구독하기) (피드랑 묶기)



### 게시글

### 1. 공감 

### 2. 수정 / 삭제

### 3. 댓글 쓰기

### 4. 공개 / 비공개

### 5. 게시글 쓰기

