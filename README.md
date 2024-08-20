![image](https://github.com/user-attachments/assets/80fc49d7-565c-4d10-9104-88b5792414ab)
<div align=center>
  
  **🦅[Play Data] 한화시스템 BEYOND SW캠프 7기/불사조🦅**
</div>

<br><br>
## 👥 팀원 소개
<br><br><br>

## 🏨 프로젝트 소개
<br><br><br>

## 📢 요구사항 명세서
<br><br><br>

## ⚙️ 기술 스택
<br><br><br>

## ✈️ WBS
![image](https://github.com/user-attachments/assets/b62cbf6f-c7f1-4a00-aa94-06701a09f7af)

<div align=center>

  [⬆️WBS바로가기](https://docs.google.com/spreadsheets/d/1X0fafalLJS0A_FwmI4IMyJMZsv2F3uoe/edit?usp=sharing&ouid=106399302288862850251&rtpof=true&sd=true)
</div>
<br><br><br>

## 😊 ERD
![image](https://github.com/user-attachments/assets/03bd6cc7-4ecc-4e9a-961e-20c05261f2e3)

<br><br><br> 

## 🧪 테스트 결과 
### 1️⃣ 고객 페이지
<details>
  <summary>(1) 회원가입 및 로그인</summary>
  <br>

  * 이메일 인증을 통해 회원가입<br> 
    <img src="https://github.com/user-attachments/assets/6b0a5ecc-dba2-4421-b738-fd6bc329676d" width=700>
    <br><br>
  * 로그인 및 메인 페이지 조회
    <br><br>
</details>
<details>
  <summary>(2) 아이디 및 비밀번호 찾기</summary>
  <br>
  
  * 아이디 찾기
    <br><br>
  * 비밀번호 찾기
    <br><br>
</details>
<details>
  <summary>(3) QnA CRUD</summary>
  <br>
  
  * QnA 작성 및 조회 
    <br><br>
  * QnA 수정 및 삭제
    <br><br>
</details>

### 2️⃣ 고객 페이지 + 관리자 페이지 
<details>
  <summary>(1) Room(객실) 예약 </summary>
  <br>
  
  * 홈페이지를 통해 고객이 객실 예약을 진행  
    <br><br>
  * 관리자 페이지에서 객실 예약이 들어오면 실시간 알림(SSE) 조회
    <br><br>
  * ➕ 여러 개의 객실 예약이 들어온 경우 실시간 알림(SSE) 조회
    <br><br>
</details>
<details>
  <summary>(2) Dining 예약 </summary>
  <br>
  
  * 홈페이지를 통해 고객이 다이닝 예약을 진행  
    <br><br>
  * 관리자 페이지에서 다이닝 예약이 들어오면 실시간 알림(SSE) 조회
    <br><br>
  * ➕ 여러 개의 객실 예약이 들어온 경우 실시간 알림(SSE) 조회
  <br><br>
</details>
<details>
  <summary>(3) QnA에 답변 달기 </summary>
  <br>
  
  * 관리자 페이지를 통해 들어온 QnA에 답변 달기 
    <br><br>
  * 답변이 달리면 해당 고객의 페이지에 실시간 알림 숫자 업데이트
    <br><br>
</details>


### 3️⃣ 관리자 페이지 
<details>
  <summary>(0) 😊 모든 직원의 공통 작업 </summary>
  <br>

  * 로그인 및 본인의 정보 확인 
    <br><br>
  * 비밀번호 변경 
    <br><br>
  * 고객의 목록 및 상세 내역 조회 
    <br><br>
  * QnA가 등록되면 답변 달기 
    <br><br>
</details>
<details>
  <summary>(1) OFFICE 부서 직원 [최상위 직원] </summary>
  <br>
  
  * 모든 직원들의 목록 조회 (검색 기능)
    <br><br>
  * 직원의 상세 내역 조회 및 직급 변경 / 퇴사처리 
    <br><br>
  * 새로 입사한 직원을 등록
    <br><br>
  * ➕ Room/Dining 예약 내역 조회 불가 (권한 없음)
    <br><br>
</details>
<details>
  <summary>(2) Room(객실) 부서 직원 </summary>
  <br>
  
  * 조회하고자 하는 고객의 이메일을 검색하여 객실 예약 내역 조회 
    <br><br>
  * 객실 예약 상세 내역 조회 / 수정 / 삭제
    <br><br>
  * 객실의 base price 변경 
    <br><br>
</details>
<details>
  <summary>(3) Dining 부서 직원 </summary>
  <br>
  
  * 조회하고자 하는 고객의 이메일을 검색하여 다이닝 예약 내역 조회 
    <br><br>
  * 다이닝 예약 상세 내역 조회 / 수정 / 삭제
    <br><br>
  * 각 다이닝별 메뉴 추가 / 가격 수정 / 삭제
    <br><br>
</details>

### 4️⃣ Rabbit mq를 활용한 대기열 구현 (객실 예약 접근 ) 




