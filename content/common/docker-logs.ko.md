---
author: ['Proscream']
date: 1579618474
title: "docker logs, TLDR Pages"
description: "docker logs, 컨테이너 로그들을 출력한다."
categories: "common"
---
> 더 많은 정보: <https://docs.docker.com/engine/reference/commandline/logs>.

- 컨테이너로부터 로그들을 출력하기:

```bash
docker logs 컨테이너_이름
```

- 로그들을 출력하고 추적하기:

```bash
docker logs -f 컨테이너_이름
```

- 최근 5줄만 출력하기:

```bash
docker logs 컨테이너_이름 --tail 5
```

- 로그들을 출력하고 타임스태프 추가하기:

```bash
docker logs -t 컨테이너_이름
```

- 특정 시점의 컨테이너 실행 시점으로부터 로그 출력하기 (예시. 23m, 10s, 2013-01-02T13:23:37):

```bash
docker logs 컨테이너_이름 --until 시간
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Proscream](mailto:proscream@naver.com) | docker-logs: Add Korean Translation (#3772) | 2020-01-21T15:54:34 | [f77b6870b3c8](https://github.com/tldr-pages/tldr/commit/f77b6870b3c8ac3181d04eb95a3c8a097436f155)

