# 2018 Second Grade Project

NoNamed 동아리의 17학번 5명이서 진행하는 **똑똑한 거울** 프로젝트

# Members

### 20303 김현우
### 20308 손영동
### 20311 오준영
### 20315 이소연
### 20318 장지원

# Contents

### App
- 일정 관련 기능
  ex) 약속 시간까지 XX분 남았습니다.
- Youtuve Share API를 이용하여 원하는 영상 재생

### Server
- App과 RPi 사이의 데이터 처리 담당(일정, Youtube)

### H/W
- RPi
    - 날씨 API
    - 시간
    - 뉴스 헤드라인
    - GUI
    - Idle 모드 (미정)
- Frame
- Peripheral
    - 모니터
    - 공유기: 무선으로 Smart Mirror

# Rules

### Direction
- 프로젝트 개발 기간
    - 12월 말까지
- Issue 관리
    - 3-5일 이내에 해결 (회의)
- 매주 금요일마다 중간 점검

### Source Control
- 작업 하기 전에, pull을 이용하여 최신 버전 유지
- commit 등의 작업은 master가 아닌 해당 파트의 브랜치로 작업할 것.
- IDE 사용시 .gitignore에 소스 이외의 파일 추가

### Document
- 모든 구현 과정은 문서로 남길 것
    - word, 한글, markdown, Github Wiki 등
    - 함수와 함수의 기능, 리턴 등 작성
    - 프로그램 실행 순서가 아닌 동작 원리등 소스를 읽기만 해서는 알 수 없는 부분 작성
- 개발한 소스의 내용 뿐만 아니라 개념적으로 관련된 부분도 포함

### Naming
- 파일명: 단어 첫글자 마다 대문자 
> #inclued <ApplePie.h>
- 함수명: 첫 글자는 대문자, 이후 언더바 
> void Apple_pie()
- 변수명: 모두 소문자에 언더바
> int apple_pie 