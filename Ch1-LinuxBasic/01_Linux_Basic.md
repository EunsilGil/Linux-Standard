# Linux Basic

## 정의

- Unix 계열의 오픈소스 운영체제 or 커널

## 특징

- 리눅스는 오픈소스 소프트웨어로 모든 소스가 공개되어 있으므로, 자신이 원하는 대로 프로그램을 수정하여 사용하고, 다시 배포할 수 있다.
- Unix와의 완벽한 호환성을 유지한다.
- 서버용 운영체제로 많이 사용된다.
  - 기본적으로 리눅스는 서버용 운영체제로 사용되지만, 데스크탑, 임베디드 시스템, 안드로이드에 사용되기도 한다.
- 편리한 GUI 환경을 제공한다.
- 수백 개의 Linux 배포판이 사용되고 있지만, 크게 레드햇(Redhat) 계열과 데비안(Debian) 계열, 슬랙웨어(Slackware) 계열로 구분할 수 있다.
  - 기본적인 사용에는 큰 차이가 없지만, 각 계열에 따라 패키지 관리 명령 등 일부 기능이 다르므로 주의해야 한다.

**GBC과정 중에서는 그 중에서도 데비안 계열 우분투 리눅스를 사용할 예정이다.**

**우분투는 데비안 GNU/리눅스에 기초하며 유니티라는 독자적인 데스크톱 환경을 사용한다.**

## 구조

- 커널(kernel) 
  - 리눅스의 핵심
  - 프로세스 관리, 메모리 관리, 파일 시스템 관리, 장치 관리 등 컴퓨터의 모든 자원을 초기화하고 제어
- 셀(shell)
  - 리눅스의 사용자 인터페이스
  - 사용자와 커널 사이의 중간자 역할을 담당
- 응용 프로그램
  - 각종 프로그래밍 개발 도구, 문서 편집 도구, 네트워크 관련 도구 등
