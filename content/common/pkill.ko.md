---
author: ['Choi Young-jin']
date: 1652056879
title: "pkill, TLDR Pages"
description: "pkill, 프로세스 이름에 따라 시그널을 전송합니다."
categories: "common"
---
> 주로 프로세스를 종료하는데 사용합니다.

> 더 많은 정보: <https://www.man7.org/linux/man-pages/man1/pkill.1.html>.

- 일치하는 모든 프로세스 종료:

```bash
pkill "프로세스_이름"
```

- 프로세스 이름 대신 전체 명령어와 일치하는 모든 프로세스 종료:

```bash
pkill -f "명령어_이름"
```

- 강제로 일치하는 프로세스 종료 (차단 불가능):

```bash
pkill -9 "프로세스_이름"
```

- 일치하는 프로세스에게 SIGUSR1 시그널 전송:

```bash
pkill -USR1 "프로세스_이름"
```

- 브라우저를 닫기 위해 주요 `firefox` 프로세스를 종료:

```bash
pkill --oldest "firefox"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | grep, kill, lsof, pkill: add Korean translation (#8061) | 2022-05-09T02:41:19 | [380047459f50](https://github.com/tldr-pages/tldr/commit/380047459f50917cf90c2a338a40951a8430e5f6)

