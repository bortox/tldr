---
author: ['Marco Bonelli', 'Proscream']
date: 1574435377
title: "chisel, TLDR Pages"
description: "chisel, Chisel은 TCP 터널을 생성하는 도구."
categories: "common"
---
> 클라이언트와 서버 모두 포함.

> 더 많은 정보: <https://github.com/jpillora/chisel>.

- chisel 서버 실행:

```bash
chisel 
```

- 특정 포트를 수신하는 chisel 서버 실행:

```bash
chisel server -p 서버_포트
```

- 사용자 이름 및 암호 인증을 사용하여 연결을 보호하는 chisel 서버 실행:

```bash
chisel server --auth 사용자이름:비밀번호
```

- chisel 서버에 연결하고 특정 포트를 원격 서버 와 포트에 터널링:

```bash
chisel client 서버_IP:서버_포트 로컬_포트:원격_서버:원격_포트
```

- chisel 서버에 연결하고 특정 호스트와 포트를 원격 서버 및 포트에 터널링:

```bash
chisel client 서버_IP:서버_포트 로컬_호스트:로컬_포트:원격_서버:원격_포트
```

- 사용자 이름 및 암호 인증을 사용하여 chisel 서버에 연결:

```bash
chisel client --auth 사용자이름:비밀번호 서버_IP:서버_포트 local_port:원격_서버:원격_포트
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | Multiple pages(chisel to chroot) : Add Korean Translation (#3586) | 2019-11-19T18:22:39 | [bfbe15c8e437](https://github.com/tldr-pages/tldr/commit/bfbe15c8e4378a26e43b9dfe6f4ce65e2222df02)

