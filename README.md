## 협동 로봇과 PLC 연동 제어 시스템
---

### 프로젝트 개요
본 프로젝트는 PLC가 로봇의 태스크 실행, 일시정지, 재개, 정지와 작업 위치를 지정하고 로봇의 그리퍼 센서와 상태를 PLC에서 확인하는 구조로 설계하였다.
두산 매뉴얼 상 태스크 제어 신호는 이더넷으로 송신할 수 없어 명령은 I/O 직배선으로, 데이터와 상태는 Ethernet/IP 통신으로 나누어 설계하였다.

---

## Tech Stack

![Sysmac Studio](https://img.shields.io/badge/Sysmac%20Studio-005EB8?style=flat)
![DRL](https://img.shields.io/badge/Doosan%20DRL-0072CE?style=flat)

### Software
| 구분 | 사용 툴 / 언어 | 용도 |
|---|---|---|
| PLC | Omron Sysmac Studio | 직접 제어·상태·공정 시퀀스 제어 |
| 로봇 | Doosan Robotics DRL | 로봇 동작 및 작업 시퀀스 프로그래밍 |

### Hardware
| 장비 | 모델 | 용도 |
|---|---|---|
| 협동 로봇 | Doosan (A0509) | 척 pick&place |
| PLC | Omron (NX102-1020) | 공정 제어 |
| HMI | Omron (NA5-9W001B) | 터치 패널 (UI) |
| Vision | Omron (FZ-SQ050F) | 비전 카메라 |

---

프로젝트 기획 배경, 시스템 구성, 모델 학습 과정 및 구현 상세 내용은 아래 블로그에 정리되어 있습니다.
[프로젝트 상세 설명 보러 가기] (https://xiin.tistory.com/49)
