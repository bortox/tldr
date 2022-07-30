---
author: ['Schneider', 'Proscream']
date: 1584042729
title: "docker-machine"
description: "docker-machine, 도커를 실행하는 머신들을 생성하고 관리한다."
categories: "common"
---
> 더 많은 정보: <https://docs.docker.com/machine/reference/>.

- 현재 실행중인 도커 머신들 목록보기:

```bash
docker-machine ls
```

- 특정 이름으로 새로운 도커 머신 생성하기:

```bash
docker-machine create 이름
```

- 머신의 상태 가져오기:

```bash
docker-machine status 이름
```

- 머신 시작하기:

```bash
docker-machine start 이름
```

- 머신 중지하기:

```bash
docker-machine stop 이름
```

- 머신에 대한 정보 검사하기:

```bash
docker-machine inspect 이름
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Proscream](mailto:proscream@naver.com) | docker-machine : Add Korean Translation (#3819) * docker-machine : Add Korean Translation * Update pages.ko/common/docker-machine.md [...] | 2020-02-01T12:59:42 | [c46c039b6609](https://github.com/tldr-pages/tldr/commit/c46c039b6609b5f401fbbaa35a098c2e7f868854)

