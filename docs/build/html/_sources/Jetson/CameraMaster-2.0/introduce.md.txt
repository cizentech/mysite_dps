# Introduction to CameraMaster-2.0

## CameraMaster-2.0 개요
CameraMaster-2.0은 Ubuntu 22.04 환경에서 동작하는 고성능 카메라 관리 소프트웨어입니다.
이 프로그램은 OpenCV와 CUDA를 활용하여 영상 처리 성능을 최적화하며, **GTK4 기반의 직관적인 사용자 인터페이스(UI)** 를 제공합니다.
특히 NVIDIA Jetson Orin 시리즈와 완벽한 호환성을 가지며, Jetson의 강력한 GPU 가속 기능을 활용하여 실시간 영상 처리 및 AI 기반 영상 분석을 지원합니다.

또한, **GStreamer** 기반의 영상 처리 기능을 지원하며, **ISP** (이미지 신호 프로세서) 적용이 가능하며, 요청 시 커스터마이징이 가능합니다.
이를 통해 사용자는 최적화된 영상 파이프라인을 구성하고, **Jetson** 하드웨어의 성능을 극대화할 수 있습니다.

## CameraMaster-2.0의 주요 특징

###  Ubuntu 22.04 운영 체제 기반
CameraMaster-2.0은 최신 장기 지원(LTS) 버전인 Ubuntu 22.04 환경에서 최적화되었습니다.
이를 통해 최신 커널 및 드라이버를 활용할 수 있으며, Jetson 플랫폼에서 안정적인 소프트웨어 운영이 가능합니다.

### OpenCV 및 CUDA 기반 영상 처리
-  **OpenCV (Open Source Computer Vision Library)** 를 활용하여 고속 영상 처리 및 필터링 기능을 제공합니다.
- CUDA(Compute Unified Device Architecture) 지원을 통해 GPU 가속 기반의 영상 프로세싱 성능을 극대화할 수 있습니다.
- Jetson Orin의 강력한 AI 엔진과 CUDA 코어를 활용하여 실시간 영상 분석 및 객체 탐지가 가능합니다.

### GStreamer 기반 영상 처리 지원
- **GStreamer** 는 멀티미디어 스트리밍을 위한 오픈소스 프레임워크로, **Jetson** 의 하드웨어 가속을 활용한 효율적인 영상 처리 기능을 제공합니다.
- 하드웨어 기반 **ISP** (이미지 신호 프로세서) 적용 가능, 이를 통해 노이즈 제거, 화이트 밸런스 조정 등 최적의 영상 품질을 구현할 수 있습니다.
- 요청 시 커스터마이징 가능, 특정 요구 사항에 맞게 영상 처리 파이프라인을 조정할 수 있습니다.


### GTK4 기반 UI 인터페이스
- 최신 UI 프레임워크인 **GTK4** 를 기반으로 설계되어, 반응성이 뛰어나고 직관적인 사용자 경험(UX)을 제공합니다.
- 사용자가 손쉽게 영상 재생, 설정 변경, 카메라 관리 등을 수행할 수 있도록 **직관적인 UI** 구성이 적용되었습니다.
-  **다중 카메라 지원** 및 사용자 맞춤형 영상 설정 기능을 제공합니다.

### NVIDIA Jetson Orin 시리즈와 호환
- Jetson Orin Nano, Jetson Orin NX, Jetson AGX Orin 등 최신 Jetson 시리즈와 완벽한 호환성을 제공합니다.
- Jetson Orin의 강력한 GPU 및 NPU를 활용하여 고성능의 실시간 영상 처리 및 AI 기반 객체 인식 기능을 실행할 수 있습니다.
- JetPack SDK 및 DeepStream과의 연계를 통해 AI 모델을 최적화하여 영상 분석 성능을 향상시킬 수 있습니다.

## CameraMaster-2.0을 활용할 수 있는 분야
CameraMaster-2.0은 고성능 영상 처리 및 AI 분석을 필요로 하는 다양한 분야에서 활용될 수 있습니다.

✔ 스마트 공장 및 산업용 모니터링

✔ 자율 주행 및 로봇 비전 시스템

✔ 보안 감시 및 스마트 CCTV 시스템

✔ AI 기반 의료 영상 분석

✔ 드론 및 실시간 항공 촬영 영상 처리



