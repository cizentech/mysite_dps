# Install

이 가이드는 Jetson Orin 및 Ubuntu 22.04 환경에서 DriverMaster 를  설치하는 방법을 설명합니다.
설치는 크게 시스템 업데이트, 설치 파일 다운로드 2가지로 진행됩니다.

## 시스템 업데이트 및 업그레이드

설치 전, 시스템을 최신 상태로 유지하기 위해 패키지 목록을 업데이트하고 설치된 패키지를 업그레이드해야 합니다.

```sh
sudo apt update && sudo apt upgrade -y
```

⚠ 주의: 시스템 업데이트 및 업그레이드는 네트워크 연결이 필요합니다.

## 설치 프로그램 다운로드
DriverMaster 설치 파일 (.deb 패키지)을 다운로드합니다.

```sh
wget <url>
```

- wget 명령을 사용하여 CameraMaster-2.0 패키지를 다운로드합니다.
- <설치 파일 URL> 부분은 제공예정

## DriverMaster 실행

```sh
cd DriverMaster
sudo python3 DriverMaster.py
```

**주의사항**: 터미널 창의 크기가 최소 요구사항보다 작을 경우 프로그램이 정상적으로 실행되지 않을 수 있습니다. 이러한 경우 터미널 창을 확장하여 최소 권장 크기(80x24)로 조정하십시오.

