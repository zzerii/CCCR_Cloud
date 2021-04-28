# Ubuntu 방화벽 설정

### 방화벽 켜기

```
$ sudo ufw enable
```

### 방화벽 끄기

```
$ sudo ufw disable
```

### 특정 port allow

```
$ sudo ufw allow 1234/tcp
```

1234 port의 tcp를 open

### 특정 port deny

```
$ sudo ufw deny 1234/tcp
```

### 규칙 제거

```
$ sudo ufw delete allow 1234/tcp
$ sudo ufw delete deny 1234/tcp
```

delete 후에 allow or deny 

### 특정 IP 막기

```
$ sudo ufw deny from [IP]
```

### 상태 확인 하기

```
$ sudo ufw status
```