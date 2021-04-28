# Ubuntu apt-get 명령어 정리

**패키지 인덱스 정보 업데이트:**

`$ sudo apt-get update`

**설치된 패키지 업그레이드:** 설치되어 있는 패키지를 모두 새 버전으로 업그래이드 합니다.

`$ sudo apt-get upgrade`

의존성 검사 하며 설치

`$ sudo apt-get dist-upgrade`

**패키지 설치**

`$ sudo apt-get install`

**패키지 재설치**

`$ sudo apt-get --reinstall install 패키지 이름`

**패키지 삭제**

설정파일은 지우지 않음

`$ sudo apt-get remove 패키지 이름`

설정 파일까지 모두 지움

`$ sudo apt-get --purge remove 패키지 이름`

**패키지 소스코드 다운로드**

`$ sudo apt-get source 패키지 이름`

위에서 받은 소스코드를 의존성 있게 빌드

`$ sudo apt-get build-dep 패키지 이름`

**패키지 검색**

`$ sudo apt-cache search 패키지 이름`

**패키지 정보 보기**

`$ sudo apt-cache show 패키지 이름`