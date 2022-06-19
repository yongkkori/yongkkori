# 임베디드프로젝트_1701249김용호_701274 온기환

## 1.프로젝트 설명
- Jetson Nano, Arduino nano rp2040를 사용하였으며, 두 기기 사이에 MQTT 브로커를 통해 TOPIC을 설정하고 Publish,Subscribe 한 후 Node-RED DashBoard에 결과값을 도출해냄.
- Jetson Nano의 미리 설치된 Mediapipe를 사용하여 Rock,Scissor,Paper를 구별해 검출결과를 DashBoard에서 확인 할 수 있음.
- Arduino nano rp2040의 IMU센서를 통해 사용자의 가속도를 실시간으로 측정해  Walking 상태인지 Stop상태인지 DashBoard에 확인 할 수 있음.

## 2.Node-RED 플로우
