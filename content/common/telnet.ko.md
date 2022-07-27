---
author: ['Choi Young-jin']
date: 1649332153
title: "telnet, TLDR Pages"
description: "telnet, telnet 프로토콜을 사용해 호스트의 특정 포트에 연결합니다."
categories: "common"
---
> 더 많은 정보: <https://manned.org/telnet>.

- 호스트의 기본 포트에 Telnet 연결:

```bash
telnet 호스트
```

- 호스트의 특정 포트에 Telnet 연결:

```bash
telnet ip_주소 포트
```

- Telnet 세션 종료:

```bash
quit
```

- 세션 종료를 위한 기본 이스케이프 문자 조합을 전송:

```bash
Ctrl + ]
```

- "x"를 세션 종료 문자로 사용하여 세션 시작:

```bash
telnet -e x ip_주소 포트
```

- Telnet 으로 스타워즈 보기:

```bash
telnet towel.blinkenlights.nl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | nc, telnet, vim: add Korean translation (#7960) | 2022-04-07T13:49:13 | [dc7bd7365399](https://github.com/tldr-pages/tldr/commit/dc7bd7365399837466c7f78637939756109f672b)

