# 2026-04-13-OracleStudy
1) 데이터 정의어(DDL: Data Definition Language)
- 데이터 베이스 스키마를 DBMS가 이해할 수 있도록 기술하는데 이용
- 데이터베이스 관리자, 설계자가 주로 사용
- CREATE / ALTER / DROP / RENAME / TRUNCATE
2) 데이터 조작어(DML: Data Manipulation Language)
- 사용자가 DMS로 하여금 원하는 데이터를 처리하게끔 명세하는 도구
- 사용자(응용 프로그램)와 DBMS간 인터페이스 제공
- 검색, 삽입, 삭제, 변경등을 포함
  * 데이터 언어의 완전성
  * 사용자가 원하는 데이터베이스의 어떤 객체도 추출할 수 있고 처리할 수 있으며 어떤 관계도 표현할 수 있는 데이터 언어의 능력을 말함
- INSERT / UPDATE / DELETE
3) 데이터 제어어(DCL: Data Control Language)
- 데이터 보안, 무결성, 회복, 병행 수행 제어를 명세할 수 있는 명령어들을 포함
- 주로 관리목적으로 데이터베이스 관리자가 사용함
- GRANT / REVOKE
4) 질의어(DQL: Data Query Language)
- SELECT : 데이터 검색
5) 트랜젝션 처리(TCL: Transaction Control Language)
- COMMIT / ROLLBACK / SAVEPOINT

 - DISTINCT : 중복되는 행을 제거하는 옵션입니다.
 - alias    :  해당 column에 대해서 다른 이름을 부여할 때 사용합니다. 
 - table_name :  질의 대상 테이블명
 - WHERE    :   조건을 만족하는 행들만 검색
 - condition :  column, 표현식, 상수 및 비교 연산자
 - ORDER BY  :   질의 결과 정렬을 위한 옵션(ASC:오름차순(Default)
                 ,DESC내림차순)

데이터 무결성 제약 조건 (Data Integrity Constraint Rule) 
테이블에 부적절한 자료가 입력되는 것을 방지하기 위해 테이블 생성 시 각 컬럼에 적용하는 여러 가지 규칙

기본키(PK:Primary Key)
한 릴레이션에 후보 키가 두 개 이상 있을 경우이들 중 하나를 기본 키로 선정

외래 키(FK:Foreign Key)
어떤 릴레이션의 기본 키를 참조하는 애트리뷰트
관계 데이터베이스에서 릴레이션들 간의 관계를 나타내기 위해서 사용 (PK-FK)

SELECT * FROM 테이블이름 WHERE 검색조건 GROUP BY 속성이름 HAVING 검색조건 ORDER BY 속성이름 [ASC|DESC] 

