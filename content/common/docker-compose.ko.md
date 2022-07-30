---
author: ['Proscream', 'Locour']
date: 1634145825
title: "docker-compose"
description: "docker-compose, 다중 도커 응용 프로그램 실행 및 관리합니다."
categories: "common"
---
> 더 많은 정보: <https://docs.docker.com/compose/reference/>.

- 실행 중인 모든 컨테이너들 목록:

```bash
docker-compose ps
```

- 현재 디렉토리로로부터 `docker-compose.yml` 파일을 사용하여 백그라운드에서 모든 컨테이너들을 생성하고 실행하기:

```bash
docker-compose up -d
```

- 모든 컨테이너들을 실행하고, 필요 시 재조립:

```bash
docker-compose up --build
```

- 대체 구성 파일을 사용하여 모든 컨테이너들 실행하기:

```bash
docker-compose --file 경로/파일명 up
```

- 실행중인 모든 컨테이너들 중지하기:

```bash
docker-compose stop
```

- 모든 컨테이너들, 네트워크, 이미지, 그리고 볼륨을 중지하고 제거하기:

```bash
docker-compose down --rmi all --volumes
```

- 모든 컨테이너들에 대한 로그들 팔로우:

```bash
docker-compose logs --follow
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[Proscream](mailto:proscream@naver.com) | docker-compose : Add Korean Translation (#3757) | 2020-01-14T20:00:28 | [17c2bfaeec2f](https://github.com/tldr-pages/tldr/commit/17c2bfaeec2f1f07dbaf329d29b0fb9083620a34)

