---
author: ['Choi Young-jin']
date: 1652056879
title: "kill, TLDR Pages"
description: "kill, 보통 프로세스를 정지시키는 것과 관련된 시그널을 전송합니다."
categories: "common"
---
> SIGKILL과 SIGSTOP을 제외한 모든 시그널들은 깔끔한 종료를 위해 프로세스에게 뺏길 수 있습니다.

> 더 많은 정보: <https://manned.org/kill>.

- 기본 SIGTERM ("terminate") 시그널을 보내 프로그램을 종료:

```bash
kill 프로세스_아이디
```

- 사용 가능한 시그널 이름을 출력 (`SIG` 접두사는 없이 출력):

```bash
kill -l
```

- 백그라운드 job 종료:

```bash
kill %job_아이디
```

- SIGHUP ("hang up") 시그널을 사용해서 프로그램을 종료. 대다수의 데몬(백그라운드 프로세스)은 종료하는 대신 리로드 함:

```bash
kill -1|HUP 프로세스_아이디
```

- SIGINT ("interrupt") 시그널을 사용해서 프로그램을 종료. 이건 일반적으로 사용자가 `Ctrl + c`를 누를 때 일어나는 일과 같음:

```bash
kill -2|INT 프로세스_아이디
```

- 운영체제에게 즉시 프로그램을 종료하라는 시그널을 전송 (프로세스가 신호를 받지 못하고 종료됨):

```bash
kill -9|KILL 프로세스_아이디
```

- 운영체제에게 SIGCONT ("continue") 시그널을 받기 전까지 프로그램을 일시정지하라는 시그널을 전송:

```bash
kill -17|STOP 프로세스_아이디
```

- 주어진 GID (그룹 아이디)를 가진 모든 프로세스에게 `SIGUSR1` 시그널을 전송:

```bash
kill -SIGUSR1 -그룹_아이디
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | grep, kill, lsof, pkill: add Korean translation (#8061) | 2022-05-09T02:41:19 | [380047459f50](https://github.com/tldr-pages/tldr/commit/380047459f50917cf90c2a338a40951a8430e5f6)

