---
author: ['Proscream']
date: 1580658261
title: "docker"
description: "docker, 도커 컨테이너들과 이미지들을 관리한다."
categories: "common"
---
> 더 많은 정보: <https://docs.docker.com/engine/reference/commandline/cli/>.

- 현재 실행중인 도커 컨테이너들 목록보기:

```bash
docker ps
```

- 모든 도커 컨테이너들(실행중이고 중지된) 목록 보기:

```bash
docker ps -a
```

- 사용자 정의 이름으로 이미지로부터 컨테이너 실행:

```bash
docker run --name 컨테이너_이름 이미지
```

- 기존 컨테이너 실행 또는 중지하기:

```bash
docker 실행|중지 컨테이너_이름
```

- 도커 레지스트리로부터 이미지 가져오기:

```bash
docker pull 이미지
```

- 이미 실행중인 컨테이너 내부에서 쉘 열기:

```bash
docker exec -it 컨테이너_이름 쉘
```

- 중지된 컨테이너 제거하기:

```bash
docker rm 컨테이너_이름
```

- 컨테이너 로그를 가져오고 팔로우하기:

```bash
docker logs -f 컨테이너_이름
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Proscream](mailto:proscream@naver.com) | docker : Add Korean Translation (#3829) | 2020-02-02T16:44:21 | [bd6faf01083a](https://github.com/tldr-pages/tldr/commit/bd6faf01083ae34eda815100cf96743627d8935a)

