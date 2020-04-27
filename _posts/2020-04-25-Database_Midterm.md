---
title:  "[Database] Midterm Project"
excerpt: ""

categories:
  - Howto

tags:
  - 데이터베이스
---

- # Database

  Database 중간 대체 과제 프로젝트 임시 저장 POST 입니다.

  

  ## 요구사항
  
  1. 기존에 주어진 데이터베이스에서 Book, Orders, Customer Table에 각각 10개, 10개, 5개의 새로운 튜플 추가
  2. 초기화 버튼 : 본인이 추가한 데이터를 포함해서 3개의 테이블에 대한 데이터를 초기화 한다. 즉, book/orders 테이블은 20개의 튜플로 초기화 하고, customer 테이블은 10개 튜플로 초기화 한다.
  3. 입력1 버튼 : orders 테이블에 새로운 튜플을 추가한다. 새로운 데이터는 키보드에서 입력받도록 UI를 구성한다. 단, 제약조건을 벗어난 입력값에 대해서는 적절한 오류 메시지를 표시하고 입력이 안 되어야 한다. 
  4. 검색1 버튼 : select * from book 쿼리를 실행한 결과를 표시한다.
  5. 검색2 버튼 : select * from orders 쿼리를 실핸한 결과를 표시한다.
  6. 검색3 버튼 : select * from customer 쿼리를 실행한 결과를 표시한다.
  
  
  

현재 구현 완료 : 초기화 , 검색1, 검색2, 검색3 완료 !

현재 구현 완료 : 입력 UI 구현 완료 !

내일 해야 할 일 : 입력 UI 통해 데이터 값 읽어와서 데이터베이스에 INSERT 하기



2020-04-26 (일)

기능 구현 전부 완료 !

주석 달고 코드 리팩토링 하면 끝 !

그리고 제약조건 위반한 입력 발생 시 오류 메시지 콘솔 창에 띄우는지 UI에 띄우는지 메일 확인 할 것



2020-04-27 (월)

메일 확인 결과 오류 메시지는 원하는 곳에 띄우면 됨

UI에는 오류가 발생했으니 콘솔창을 확인하라는 메시지 출력

데스크탑과 맥북에서 모두 동작하는 것 확인

수요일에 코드, 주석 더 다듬어서 제출하기 !