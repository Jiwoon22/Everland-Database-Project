<br>
<h1 align="center"> 데이터베이스 설계 과제 </h1>
<h2 align="center"> Oracle 데이터베이스를 활용한 놀이공원 DB 설계  </h2>
<br>

---
### 설계 과제 목표
- 에버랜드를 기반으로, 놀이동산 시스템 속에서 발생하는 데이터를 분석하고 분석된 데이터를 토대로 개념적, 논리적, 물리적 설계를 진행하여 각 모델을 토대로 한 데이터 관리 시스템 개발을 목표로 한다.   
* ORACLE의 이해
* DDL, DML, DCL 숙련도 제고
* 데이터베이스의 전반적인 이해(키 설정, 정규화, 제약사항 파악 등)
 
### 요구사항 분석
* 개념적 설계 (ER 다이어그램 작성)
* 논리적 설계 (데이터베이스 테이블 작성)
* 물리적 설계 (뷰, 테이블 스키마 작성)
  
***ER 다이어그램***
-
![image](https://github.com/Jiwoon22/Everland-Database-Project/assets/51106092/b6611462-f0c7-49dc-b73f-4b5d1498324f)


***작성된 테이블***
-
![image](https://github.com/Jiwoon22/Everland-Database-Project/assets/51106092/64c0b5d3-ce8c-4fb0-872b-3b521dcc0619)


-	다른 클라이언트가 서버에 접속 종료 시 스레드를 할당 받아 해당 데이터를 불러온다.
