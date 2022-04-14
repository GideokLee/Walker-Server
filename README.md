# 🚶 Walker
## ❓ Walker 소개
### 주요 기능
- BLE 통신
    - Walker와 안드로이드 기기간의 BLE 통신
    - 일일, 주간, 월간 사용 기록 확인
    - 당일 상세 기록 확인
- 알람
    - 장치 사용 시작, 종료 알람
    - 
## WALKER API GUIDE
### 로그인 화면
/login/{id}{pwd}
### 회원 등록 화면
/signup/{id}{pwd}{name}
### 사용 로그 화면
/log-day/id/{date}
/log-week/id/{date}
/log-month/id/{date}
### 알람 목록 화면
/alam/{id}
### BLE 장치
/log{data}
