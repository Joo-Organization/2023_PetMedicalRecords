MVC 모델 기반 애완동물 진료 기록 관리 시스템 (연습용)
Java,파일입출력,파일변환(Json,CSV),예외처리를 이용한 신규 고객 정보 추가, 진료 기록 저장, 삭제 및 프로그램 종료 구현

<프로젝트 소개>
애완동물 진료 기록 관리 시스템

<개발 기간>
2023.12.08

<개발환경>
Languages : Java 17
Build Tool : Maven
Test : Junit 5
DB : X
Version Control System : Git + Github

메인리스트 입출력 화면구현
입력받는 메뉴번호로 각 화면 연결
메인 내 공통 exception 처리 구현


특정 고객에 대한 진료 기록 조회
진료 기록 조회 및 입출력 화면 구현


<공통>
코드 리팩토링
예외처리
패키지 구성
MVC 패턴을 활용한 패키지 구성

Model : Customer, MedicalRecord
View : ConsoleView
Controller : CustomerController, MedicalRecordController

웹 프로젝트에서는 View 에서 Controller 호출 시 데이터를 넘겨주지만 Console 에선 구현하기 어렵다.

Common : 공통으로 사용될 유틸, 코드, 메세지 등 정의
Application : 자바 애플리케이션 실행부 입니다.

프로젝트의 기능
메인화면
Application.java 의 run() 메서드에 구성되어있고 입력값에 따른 메뉴이동 구현 및 RuntimeException 공통 처리

 




