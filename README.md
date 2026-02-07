🐱 말랑콩냥 키우기 (WinForms 클리커 게임)

C# Windows Forms를 사용해 제작한 간단한 방치형 클리커 게임입니다.
고양이 캐릭터를 클릭하고, 사료와 뽑기 시스템을 활용해 수익을 늘리는 구조의 게임입니다.

📌 프로젝트 개요

프로젝트명: 말랑콩냥 키우기

장르: 방치형 / 클리커 게임

개발 환경

Language: C#

Framework: .NET (Windows Forms)

플랫폼: Windows (PC)

개발 목적

WinForms 기반 UI 구성과 이벤트 처리 학습

간단한 게임 로직(확률, 수익 계산, 상태 관리) 구현 경험

🎮 게임 소개

이 게임은 고양이 캐릭터(콩냥이)를 클릭하여 재화를 획득하고,
뽑기 및 사료 시스템을 통해 더 높은 수익을 얻는 방치형 게임입니다.

메인 캐릭터 클릭 시 돈 획득

초당 수익 시스템 존재

상점 / 도감 / 뽑기 화면 제공

🖥 화면 구성

메인 화면

콩냥이 클릭

현재 돈 및 수익 확인

상점 화면

사료 구매

뽑기 실행

도감 화면

보유한 고양이 목록 확인

고양이 클릭 시 메인 캐릭터로 설정

화면 전환은 Panel을 이용해 구현됨 

윈프 피피티 말랑콩냥

🐾 캐릭터 구성
등급별 고양이

A 등급

기본냥이, 호냥이, 회냥이

기본 수익: 90원

강화 수익: +15원

S 등급

비니냥이, 폭죽냥이, 중절냥이

기본 수익: 180원

강화 수익: +45원

SR 등급

여왕냥이, 왕냥이, 할리퀸냥이

기본 수익: 450원

강화 수익: +150원

🍖 사료 시스템

사료는 일정 시간 동안 수익을 증가시키는 아이템입니다.

사료 종류	효과
일반 사료	5초간 수익 1.35배
중급 사료	5초간 수익 1.75배
고급 사료	5초간 수익 3배

사료 효과는 중첩 불가

효과 종료 시 알림 창 출력

남은 사료 개수 알림 제공 

윈프 피피티 말랑콩냥

🎲 뽑기 시스템

돈을 사용해 고양이를 랜덤으로 획득합니다.

확률 구성

일반 뽑기

SR: 15% / S: 35% / A: 50%

중급 뽑기

SR: 20% / S: 50% / A: 30%

고급 뽑기

SR: 50% / S: 35% / A: 15%

돈이 부족할 경우 알림 창 출력

성공 시 등급별 고양이 랜덤 지급 

윈프 피피티 말랑콩냥

📷 시연 화면

초기 화면
<img width="643" height="642" alt="image" src="https://github.com/user-attachments/assets/e8a23c2b-0ada-4644-86bd-eadc87e317d1" />


상점 화면
<img width="641" height="642" alt="image" src="https://github.com/user-attachments/assets/12b76f96-0896-4d31-97f5-9bc25a829484" />

뽑기 실행
<img width="648" height="650" alt="image" src="https://github.com/user-attachments/assets/6a871db1-c5b7-495e-8dfd-272628cd0b9f" />

도감 화면
<img width="670" height="653" alt="image" src="https://github.com/user-attachments/assets/e09037be-a3bd-4381-8339-08ac33a9e5e3" />

사료 지급 알림
<img width="646" height="646" alt="image" src="https://github.com/user-attachments/assets/2c03f121-c5da-4ea1-ba7f-85a38f59f5b7" />
<img width="645" height="646" alt="image" src="https://github.com/user-attachments/assets/266df4c6-b22f-4098-b479-c95d20b6483b" />
