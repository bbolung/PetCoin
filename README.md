# ♻️ Ecovery ♻️

## 📌 목차
1. [프로젝트 소개](#-프로젝트-소개)
2. [팀원 소개](#-팀원-소개)
3. [개발 환경](#-개발-환경)
4. [다이어그램](#-다이어그램)
5. [기능 설명](#-기능-설명)
6. [개선 사항](#-개선-사항)

<br>

## 📄 프로젝트 소개
**PetCoin**은 AI 불량검출을 통해 시민들이 사용할 수 있는 페트병 무인 회수기 시스템 구축 및 포인트 환급과 관리자 페이지가 있는 플랫폼입니다.
  * 페트병 무인 회수기를 설치하여 시민들이 1병당 10p를 보상받을 수 있습니다.
  * PetCoin 홈페이지에서 전화번호로 간단하게 가입할 수 있으며 2000p부터 계좌로 환급 요청할 수 있습니다.
  * 관리자 페이지에서 수거내역, 회원관리, 키오스크 관리를 할 수 있으며 포인트 환급 요청을 처리할 수 있습니다.

개발 기간 : 2025.09.01 ~ 2025.09.12

<br>

## 🙋 팀원 소개
<table>
 <tr>
  <th>노유경</th>
  <th>방희경</th>
  <th>이지혜</th>
  <th>오세희</th>
 </tr>
 <tr>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
 </tr>
 <tr>
  <td>키오스크 실행 세션<br>라우팅 리팩터링·공통API 구축<br>관리자 페이지와 태블릿 연동</td>
  <td>로그인/회원가입<br>지도 연동 기능</td>
  <td>AI 학습 모델 개발<br>AI·React·Spring 연동 Flash 서버 구축<br>마이페이지</td>
  <td>관리자 페이지 백엔드 기능 구현 및 프론트엔드 연결</td>
 </tr>
</table>

<br>

## 🔧 개발 환경
<div> 
  <h4>Back-End</h4>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <img src="https://img.shields.io/badge/MyBatis-222222?style=for-the-badge&logoColor=white">
  <br>
  
  <h4>Front-End</h4>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css&logoColor=white">  
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
  <br>

  <h4>DB</h4>
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <br>

  <h4>AI 서버</h4>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/YOLOv8-007BFC.svg?style=for-the-badge&logo=YOLOv8&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/Conveyor%20Belt-555555?style=for-the-badge&logo=gears&logoColor=white" alt="Conveyor Belt">
  <br>
  
  <h4>개발환경</h4>
  <img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">
  <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white">
  <br>

  <h4>Tool</h4>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</div>

<br>

## 📊 다이어그램
<details>
  <summary>Usecase Diagram</summary>
  <div markdown="1">
     <img src="/images/Diagram/Usecase.png" width="35%">
  </div>
</details>
<details>
  <summary>ERD</summary>
  <div markdown="1">
    <img src="/images/Diagram/ERD.png" >
  </div>
</details>

<br>

## 🔍 기능 설명
### 관리자 페이지
<details>
  <summary>대시보드 페이지</summary>
  <div markdown="1">
     <img src="images/page/dashboard.jpg" width="45%">
     <p><b>* 기능</b></p>
     <p>- 수거량, 회원, 포인트의 통계 정보 확인 가능</p>
     <p>- 키오스크 현황에 대해 간략적으로 정보 확인 가능</p>
    <br>
  </div>
  
</details>

<details>
  <summary>수거내역 페이지</summary>
  <div markdown="1">
     <img src="images/page/collection.jpg" width="80%">
     <p><b>* 기능</b></p>
     <p>- 무인 회수기의 정보 목록으로 확인 가능</p>
     <p>- 필터링 기능 사용하여 무인 회수기 단건 조회 가능</p>
    <br>
  </div>
</details>

<details>
  <summary>회원 관리 페이지</summary>
  <div markdown="1">
    <img src="images/page/member.jpg" width="80%">
    <p><b>* 기능</b></p>
    <p>- 전체 회원에 대한 통계 정보 확인 가능</p>
    <p>- 페이징 처리를 통해 한 페이지당 6명의 회원 정보 확인 가능</p>
    <br>
  </div>
</details>

<details>
  <summary>포인트 관리 페이지</summary>
  <div markdown="1">
    <p aline="center">
      <img src="images/page/point1.jpg" width="80%">
      <img src="images/page/point2.jpg" width="80%">
    </p>
    <p><b>* 기능</b></p>
    <p>- 포인트 요청 처리 상태에 따라 통계 정보 확인 가능</p>
    <p>- 전체 포인트 요청 목록으로 확인 가능</p>
    <p>- 포인트 요청 상태를 선택하여 필터링된 목록 확인 가능</p>
    <p>- 승인/거부 버튼을 클릭하여 포인트 요청 처리 가능</p>
    <p>- 승인하면 즉시 회원의 포인트 차감되고, 거부하면 포인트 반환됨</p>
    <p>- 처리한 내역 하단에서 확인 가능</p>
    <br>
  </div>
</details>

<details>
  <summary>키오스크 관리 페이지</summary>
  <div markdown="1">
    <img src="images/page/kiosk.jpg" width="80%">
    <p><b>* 기능</b></p>
    <p>- 전체 키오스크 정보 확인 가능</p>
    <p>- 키오스크 운영 상태(운영중/점검중) 설정 가능</p>
    <p>- 키오스크 실행한 내역 확인 가능</p>
    <br>
  </div>
</details>

## ⏳ 개선 사항
  * 마이페이지에 포인트 환급 요청 이외의 추가적인 서비스 추가 필요
  * 홈페이지에 공지사항이나 이벤트 등 게시판 기능 추가 필요
  * 키오스크 오류 발생하면 관리자에게 알림이 오는 서비스 기능 추가 필요
