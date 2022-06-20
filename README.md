# 임베디드시스템 최종프로젝트_1701269 서영찬, 1701302 최승호

# 1. 프로젝트 설명
- Jetson Nano, Arduino nano rp2040를 이용하였고 MQTT 브로커를 통해 Publish/Subscribe 한 결과를 Node-RED의 대시보드를 통해 쉽게 파악할 수 있도록 하였음.

- Arduino nano rp2040을 두개 이용해 IMU 센서를 통해 각 사용자의 움직임 상태를 실시간으로 Node-RED의 대시보드를 통해 확인할 수 있고 x, y, z축의 움직임을 게이지를 통해 보여줌.

- 젯슨 나노의 카메라를 통해 실시간 영상 스트리밍 및 검출되는 가위, 바위, 보 동작의 결과를 Node-RED를 통해 확인할 수 있음.

# 2. 노드레드 Flow
<img width="80%" src="https://github.com/emperor5519/Embedded-class_KunsanUniv/blob/main/imgs/node-red%20flow.png">

# 3. 노드레드 Dashboard
<img width="60%" src="https://github.com/emperor5519/Embedded-class_KunsanUniv/blob/main/imgs/node-red%20dashboard1.png">

<img width="80%" src="https://github.com/emperor5519/Embedded-class_KunsanUniv/blob/main/imgs/node-red%20dashboard2.png">

# 4. 동작 영상
[![Video Label]](https://youtu.be/tBwFnt8RhAs)
