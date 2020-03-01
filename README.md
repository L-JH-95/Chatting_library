# MINIPROJECT 2019.08.14

## <라즈베리파이를 이용한 도서관 사서/검색 프로그램>
## Usage
- **User 확인**
- **User 추가**
- **도서 검색**
- **도서 추가**
- **도서 삭제**

### User 확인
- Mysql 접근시 접근 User를 USER table과 비교
- USER table 에 존재하는 유저일 시 PW를 입력, 비교하여 접근 허가

### User 추가
- User table에 존재하지 않는 유저의 경우 PW를 입력 받아 USER table에 추가

### 도서 검색
- **input option** : title, writer, publisher 지정
- 해당 option에 존재하는 값 입력 시 search 후 client에게 결과 반환

### 도서 추가
- title, writer, publisher 값 입력 시 추가

### 도서 삭제
- **input option** : title, writer, publisher 지정
- 해당 option에 존재하는 값 입력 시 search 후 client에게 결과 반환

## MEMBER & ROLE
- **Server**  : 이대직
- **Query**   : 이주희
- **Client**    : 박석호

## 진행사항
- *2019-08-09* : raspberry pi 내부 process를 통한 gpio 활용 및 sql 조작
- *2019-08-14* : raspberry pi를 server로 활용해 sql조작/ client 접근성 향상/ GPIO 제거



## 소스코드.
- [source & exec](sol/final/)
- [server](sol/final/server.c)
- [client](sol/final/client.c)
- [mysql_1](sol/final/mysql.c)
- [mysql_2](sol/final/mysql_user.c) 

# MINIPROJECT 2019.08.06

##2019-08-14 Second Mini Project
[아이디어 회의 초안](sol/20190814_미니프로젝트_회의_초안.txt)

##2019-08-06 First Mini Project
[source & exec](sol/)
라즈베리파이를 이용한 도서관 사서/검색 프로그램