
# Django BackEnd
Django를 활용하여 간단한 게시판을 만들어보았습니다(∗❛⌄❛∗)<br>
기본적인 게시글 작성, 조회, 수정, 삭제 기능 및 회원가입, 댓글 작성 기능을 구현하였습니다(23-10-11)<br>
게시글 좋아요 기능 추가하였습니다!(23-10-16)<br>
팔로우/팔로잉 기능 추가하였습니다(23-10-17)<br>

<br>

## 개발환경
- Python 3.12.0
- Django 4.2.6
- SQLite

<br>

## 프로젝트 구조
![prject tree](./README_img/project_tree.png)

<br>

## 기능구현
1. articles
```
- 전체 게시글 조회
- 게시글 생성
- 특정 게시글 조회
- 게시글 삭제 
- 게시글 수정
- 댓글 작성
- 댓글 삭제
- 특정 게시글 좋아요
```

2. accounts
```
- 로그인 
- 회원가입
- 로그아웃
- 회원탈퇴
- 팔로우
```

<br>

## 시연영상
- 게시물/ 댓글
<img width="100%" src="./README_img/게시물작성.gif">

- 로그인/ 로그아웃/ 회원가입
<img width="100%" src="./README_img/회원관리.gif">

- 팔로우/ 회원 정보 수정
<img width="100%" src="./README_img/팔로우.gif">
