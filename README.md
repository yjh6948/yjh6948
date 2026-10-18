# 양준혁 · Yang Junhyeok

경기대학교 전자공학과 졸업예정(2027.02)이고 회로 설계와 임베디드 하드웨어를 하려고 합니다. 회로를 직접 설계하고 측정과 시뮬레이션으로 확인하는 일을 주로 해 왔습니다.

## 저장소

| 저장소 | 내용 |
|---|---|
| [axi_lite_slave](https://github.com/yjh6948/axi_lite_slave) | AXI4-Lite 슬레이브 IP RTL. 기능 테스트 13개가 놓친 프로토콜 버그를 assertion이 잡는 걸 버그 주입으로 확인 |
| [uart](https://github.com/yjh6948/uart) | 115200 baud UART 송수신기 RTL. 256개 값 전수 루프백과 stop bit 오류 검출 |
| [verif-agent](https://github.com/yjh6948/verif-agent) | 시뮬레이션이 실패하면 LLM에게 RTL 수정을 맡기고 다시 돌리는 검증 루프 |
| [exam-proctoring-capstone](https://github.com/yjh6948/exam-proctoring-capstone) | 캡스톤 2025 비대면 시험 감독 시스템. Raspberry Pi 카메라·초음파·LED·MariaDB 연동 코드와 시연 GIF |
| [paper-reproductions](https://github.com/yjh6948/paper-reproductions) | AI·하드웨어 논문 17편의 핵심 주장을 작게 직접 돌려본 기록. 재현 안 된 결과도 그대로 남김 |

## 캡스톤 프로젝트

- **[비대면 출석 및 시험 감독 시스템](https://github.com/yjh6948/exam-proctoring-capstone)** (2025) · Raspberry Pi 카메라 기반 하드웨어와 회로 설계 담당. MediaPipe·OpenCV로 부정행위·졸음·자리 비움·태도 불량 4가지 상황 판정. 초음파 센서로 접근을 감지해 카메라를 켜고 판정 결과를 LED와 MariaDB에 기록
- **스마트 자전거 보관소** (2024) · 센서 5종을 직접 고르고 통합 회로 설계. Arduino와 Raspberry Pi로 역할을 나눔. 50회 반복 시험에서 감지 정확도 98%

## 다루는 도구

Verilog · Icarus Verilog · OrCAD Capture · PSpice · 오실로스코프 · 멀티미터 · 함수발생기 · Arduino · Raspberry Pi · C/C++ · Python · OpenCV · MATLAB
