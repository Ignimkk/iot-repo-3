# 물류 관리 시스템
(기간: 2024년 04월 17일 ~ 2024년 04월 25일)
## 1. Project Introduction
### 1-1. Project Purpose
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/f7008a1a-854b-4c01-b575-bd548a47bb62" width ="800">
  </div>

### 1-2. Technology Stack
  <div align=center>
      
   |**Category**|**Details**|
  |:----------:|:----------:|
  |**DEV**|<img src="https://img.shields.io/badge/Ubuntu22.04-E95420?style=for-the-badge&logo=Ubuntu22.04&logoColor=white"> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white"> |
  |**TECH**|<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"> <img src="https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=Qt&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">|
  |**HW**| <img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=Arduino&logoColor=white">
  |**TOOL**|<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=Confluence&logoColor=white"> <br> <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> |
</div> 

### 1-3. Member Role
  <div align=center> 
  
|**구분**|**이름**|**역할**|
|:------:|:------:|:-------|
|팀장|한영철|<ul><li> 시리얼 통신, RFID 정보 입출력</li></ul>|
|팀원|김민경|<ul><li> 하드웨어 설계&제작, Conveyor 동작 제어, 분류기</li></ul>|
|팀원|박서연|<ul><li> 고객 GUI, DB 구축, DB 연동 </li></ul>|
|팀원|곽민기|<ul><li> Crane 동작 제어, 관리자 GUI, DB 연동</li></ul>|
</div> 

## 2. 👨🏻‍💻Project Design👨🏻‍💻
### 2-1. Main Process Flow Chart
* 전체 흐름도
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/220b3a9a-17bd-4a83-b19c-64bd2c0dcecf" width ="800">
  </div>
  
* 시스템 구성도
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/ba092a4c-71fd-4866-8c08-7e604488a525" width ="600">
  </div>

### 2-2. 작업장
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/77485605-e25a-4caf-b19a-abb69debb681" width ="800">
  </div>

  
## 3. :star:Main Technology:star:
### 3-1. Customer GUI ℹ️
#### 3-1-1. Sequence Diagram
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/f7d6c01c-e186-47e1-ac24-7b3738d88796" width ="800">
</div>

#### 3-1-2. features
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/c33d78d1-0633-4e22-8b38-13686146c0d6" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/7f57229b-3571-4177-b95d-456040fc90e8" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/55a9d462-4f84-4e93-868c-e65b4e72e4c2" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/a90de0d5-a836-4b85-a63e-4619c30da1aa" width ="800">
</div>

### 3-2. Customer GUI ℹ️
#### 3-2-1. Sequence Diagram
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/165a6341-463e-46e7-817f-3a185d28c2a1" width ="800">
</div>

#### 3-2-2. features
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/8b73e168-cdc8-4b1f-b1ac-a521dfc80aed" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/38e17719-16a8-4c65-a04b-fe898c889c71" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/88569b54-e682-4c8f-930d-fcbebdf12ddf" width ="800">
</div>
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/146680ae-b2fb-4032-9192-fab6f6fbbce3" width ="800">
</div>

### 3-3. Crane ℹ️
#### 3-3-1. Sequence Diagram
  <div align=center> 
      <img src="https://github.com/user-attachments/assets/f0719140-2eee-4dd9-a90d-9bc6d6b6ac5a" width ="800">
</div>

#### 3-3-2. 크레인 동작 사진
  <div align=center>
  </br>
      <img src="https://github.com/user-attachments/assets/afabcd7d-7ca2-4436-9cad-942e1186f5d1" width ="300">
      <img src="https://github.com/user-attachments/assets/b707b0e0-84d9-4b51-8727-c0294a49260c" width ="300">
  </div>

#### 3-3-3. 컨베이어 벨트 동작
  <div align=center>
  </br>
      <img src="https://github.com/user-attachments/assets/4458b2e6-549f-46e7-a68f-dcef2e94ec20" width ="300">
      <img src="https://github.com/user-attachments/assets/a967ff58-5833-4e4c-9e26-a1090a932307" width ="300">
  </div>

### 4. 전체 시연 ℹ️
[![Video Label](http://img.youtube.com/vi/WHtrfWwoElg/0.jpg)](https://youtu.be/WHtrfWwoElg)

