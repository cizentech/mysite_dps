# Install to CameraMaster-2.0

이 가이드는 Jetson Orin 및 Ubuntu 22.04 환경에서 CameraMaster-2.0을 설치하는 방법을 설명합니다.
설치는 크게 시스템 업데이트, 설치 파일 다운로드, 패키지 설치의 3단계로 진행됩니다.

## 시스템 업데이트 및 업그레이드

설치 전, 시스템을 최신 상태로 유지하기 위해 패키지 목록을 업데이트하고 설치된 패키지를 업그레이드해야 합니다.

```sh
sudo apt update && sudo apt upgrade -y
```

⚠ 주의: 시스템 업데이트 및 업그레이드는 네트워크 연결이 필요합니다.

## 설치 프로그램 다운로드
CameraMaster-2.0 설치 파일 (.deb 패키지)을 다운로드합니다.

```sh
wget <url>
```

- wget 명령을 사용하여 CameraMaster-2.0 패키지를 다운로드합니다.
- <설치 파일 URL> 부분은 제공예정

## Jetson 환경에 패키지 설치
다운로드한 .deb 패키지를 사용하여 CameraMaster-2.0을 Jetson 시스템에 설치합니다.

```sh
sudo apt install ./CameraMaster -<version>.deb
```

- apt install 명령을 사용하여 .deb 패키지를 설치합니다.
- <version> 부분을 다운로드한 파일의 버전명으로 변경해야 합니다.

⚠ 주의: 설치 중 의존성 패키지가 누락되었다는 오류가 발생할 수 있습니다. 이를 해결하려면 다음 명령어를 실행하세요.

```sh
sudo apt --fix-broken install
```

## 설치 완료 후 확인 방법
설치가 정상적으로 완료되었는지 확인하려면 다음 명령어를 실행하세요.

```sh
dpkg -l | grep CameraMaster
```

- CameraMaster-2.0이 목록에 표시되면 정상적으로 설치된 것입니다.

```sh
CameraMaster
```

- 프로그램을 실행하여 동작을 확인할 수도 있습니다.

