---
author: ['bl-ue']
date: 1615231858
title: "docker container"
description: "docker container, 도커 컨테이너들을 관리한다."
categories: "common"
---
> 더 많은 정보: <https://docs.docker.com/engine/reference/commandline/container/>.

- 현재 실행중인 도커 컨테이너들의 목록:

```bash
docker container ls
```

- 하나 혹은 더 많은 정지된 컨테이너들 실행하기:

```bash
docker container start 컨테이너1_이름 컨테이너2_이름
```

- 하나 혹은 더 많은 실행중인 컨테이너들 종료하기:

```bash
docker container kill 컨테이너_이름
```

- 하나 혹은 더 많은 실행중인 컨테이너들 중지하기:

```bash
docker container stop 컨테이너_이름
```

- 하나 혹은 더 많은 컨테이너들 내에서 모든 프로세스들 일시중지하기:

```bash
docker container pause 컨테이너_이름
```

- 하나 혹은 더 많은 컨테이너들에 대한 상세 정보 표시하기:

```bash
docker container inspect 컨테이너_이름
```

- 컨테이너의 파일 시스템을 tar 아카이브로 내보내기:

```bash
docker container export 컨테이너_이름
```

- 컨테이너의 변경점들로부터 새 이미지 생성하기:

```bash
docker container commit 컨테이너_이름
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | docker-container: sync translations with PR #5067 (#5356) | 2021-03-08T20:30:58 | [a8b4d5f55b2d](https://github.com/tldr-pages/tldr/commit/a8b4d5f55b2d93890e414c9c2e83d06f6939bcda)

