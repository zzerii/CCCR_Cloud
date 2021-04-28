# Ubuntu 버전 확인하기

```jsx
$ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 18.04.5 LTS
Release:	18.04
Codename:	bionic
```

```jsx
$ lsb_release -d
Description:	Ubuntu 18.04.5 LTS
user@user-Aspire-E5-576:~$ cat /etc/issue
Ubuntu 18.04.5 LTS \n \l
```

```jsx
$ cat /etc/os-release
NAME="Ubuntu"
VERSION="18.04.5 LTS (Bionic Beaver)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 18.04.5 LTS"
VERSION_ID="18.04"
HOME_URL="[https://www.ubuntu.com/](https://www.ubuntu.com/)"
SUPPORT_URL="[https://help.ubuntu.com/](https://help.ubuntu.com/)"
BUG_REPORT_URL="[https://bugs.launchpad.net/ubuntu/](https://bugs.launchpad.net/ubuntu/)"
PRIVACY_POLICY_URL="[https://www.ubuntu.com/legal/terms-and-policies/privacy-policy](https://www.ubuntu.com/legal/terms-and-policies/privacy-policy)"
VERSION_CODENAME=bionic
UBUNTU_CODENAME=bionic
```

```jsx

$ hostnamectl
Static hostname: user-Aspire-E5-576
Icon name: computer-laptop
Chassis: laptop
Machine ID: ebb77f32b42743a1a920a4073e6dc3cd
Boot ID: 93d1f14ea37843f9a2609992b8285d96
Operating System: Ubuntu 18.04.5 LTS
Kernel: Linux 5.4.0-72-generic
Architecture: x86-64
```

```jsx
$ cat /etc/issue
Ubuntu 18.04.5 LTS \n \l
```