---
author: ['Choi Young-jin']
date: 1649332153
title: "nc"
description: "nc, Netcat은 TCP 또는 UDP 데이터 작업을 위한 다목적 유틸리티입니다."
categories: "common"
---
> 더 많은 정보: <https://nmap.org/ncat>.

- 특정 포트에서 수신대기 및 수신한 데이터 출력:

```bash
nc -l 포트
```

- 특정 포트에 연결:

```bash
nc ip_주소 포트
```

- 타임아웃 설정:

```bash
nc -w 타임아웃_될_시간 ip_주소 포트
```

- 클라이언트가 연결 해제 된 상황에도 서버를 가동 상태로 유지:

```bash
nc -k -l 포트
```

- EOF가 들어와도 클라이언트와 연결 유지:

```bash
nc -q 타임아웃_될_시간 ip_주소
```

- 특정 호스트의 포트가 열렸는지 확인:

```bash
nc -v -z ip_주소 포트
```

- 프록시처럼 로컬 TCP 포트로부터 받은 데이터를 주어진 원격 호스트에게 전달합니다:

```bash
nc -l 로컬_포트 | nc 호스트_이름 원격_포트
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | nc, telnet, vim: add Korean translation (#7960) | 2022-04-07T13:49:13 | [dc7bd7365399](https://github.com/tldr-pages/tldr/commit/dc7bd7365399837466c7f78637939756109f672b)

