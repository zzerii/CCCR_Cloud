# Ubuntu에서 VSCode설치하기

1. curl을 설치

`$ sudo apt-get install curl`

2. 마이크로소프트 GPG 키를 다운로드하여 /etc/apt/trusted.gpg.d/ 경로에 복사

`$ sudo sh -c 'curl [https://packages.microsoft.com/keys/microsoft.asc](https://packages.microsoft.com/keys/microsoft.asc) | gpg --dearmor > /etc/apt/trusted.gpg.d/microsoft.gpg'`

3. Visual Studio Code를 다운로드 받기 위한 저장소 추가

`$ sudo sh -c 'echo "deb [arch=amd64] [https://packages.microsoft.com/repos/vscode](https://packages.microsoft.com/repos/vscode) stable main" > /etc/apt/sources.list.d/vscode.list'`

4. 추가한 저장소로부터 패키지 목록을 가져오기

`$ sudo apt update`

5. Visual Studio Code를 설치

`$ sudo apt install code`

6. 실행

`$ code`

7.  git 설치

`$ sudo apt-get install git`