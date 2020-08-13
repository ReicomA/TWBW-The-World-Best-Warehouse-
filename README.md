# TWBW The-World-Best-Warehouse
2020 IoT 디자인 캠프 해커톤 작품

## 소개
* 안전한 창고 내 관리를 위한 시큐리티 솔루션

## 기능(현재 구현된 기능)
* 온습도, 가스수치(메탄)이 일정 수치 이상 발생할 경우 공기청정기 작동
* 외부인 출입 시 초음파 센서를 이용해 감지를 하고 웹에 알람 설정
* 장마철에 폭우로 인한 창고 안에 물이 샐 경우 수위가 일정 수치 이상 일어나면 바닥의 문을 열어 물을 뺌

## 사용한 기술 및 장치
* HW
  * RedBoard(Arduino, Sensor System)
  * Raspberry Pi 3 B+ (Motor System, Main Server)
* SW
  * Flask(WAS) - Python
  * Web FrontEnd(HTML, CSS, JavaScript)
* Sensor
  * 초음파 센서 - 침입자 감자
  * DC 모터 - 환풍기
  * 서보모터 - 바닥 뚜껑
  * 온습도 센서 - 창고 내 온습도 측정
  
## 구현 문제점(해결해야 할 점)
* 레드보드(아두이노)와 라즈베리파이 간의 시리얼 통신 문제로 인한 원할한 데이터 통신이 불가
* 릴레이를 활용한 DC 모터의 작동
  
  

|이름|학과|역할|
|---|---|---|
|하정현|한국산업기술대|웹서버 구현|
|신주원|서울과학기술대|하드웨어 센서 테스트 밑 모듈 구현|
|강혜리|순천대|하드웨어 및 회로도 제작|
|우승재|동국대|하드웨어 및 회로도 제작|
