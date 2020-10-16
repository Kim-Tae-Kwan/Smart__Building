# Smart Building System

빌딩 자동화 시스템, 모니터링 시스템으로 관제할 수 있는 프로그램
> 1. Atmega128을 사용하여 온습도, 침입감지, 화재감지, 침수 감지 하고 LED, 팬, 펌프, 부저를 컨트롤 합니다.
> 2. RaspberryPi는 Atmega128과 I2C 통신을 통해 데이터 수집, 컨트롤 하며 MQTT 프로토콜로 실시간으로 C# 모니터링 시스템에 데이터를 전송하는 중간 매체입니다.
>    또한 차량 번호판 인식(OpenCV), CCTV 프레임을 실시간으로 전송합니다.
> 3. C# 모니터링 시스템은 MQTT 프로토콜로 수신한 데이터들을 Visualization 하며 컨트롤 명령어를 신합니다.

## 시연영상
![모형 앞](/readmeFile/SmartBuilding_QRCode.png)

## 하드웨어
### 1.하드웨어 구성도
![모형 앞](/readmeFile/SmartBuilding_Hardware.PNG)
### 2.하드웨어 구성
![회로도](/readmeFile/SmartBuilding_Hardware2.PNG)

## 소프트웨어 구성도
![Software](/readmeFile/SmartBuilding_Software.PNG)

## Atmega128 & RaspberryPi I2C 통신
![MQTT Server](/readmeFile/SmartBuilding_I2C.PNG)

## C# WPF GUI

![센싱](/readmeFile/SmartBuilding_WPF.PNG) 










