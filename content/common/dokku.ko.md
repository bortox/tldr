---
author: ['Schneider', 'Proscream']
date: 1584042729
title: "dokku"
description: "dokku, 도커로 구동되는 미니-Heroku (PaaS)."
categories: "common"
---
> 하나의 `git-push` 명령을 사용하여 여러 언어로 다른 앱을 쉽게 배포 할수 있습니다.

> 더 많은 정보: <https://github.com/dokku/dokku>.

- 실행중인 앱들 목록보기:

```bash
dokku apps
```

- 앱 생성하기:

```bash
dokku apps:create 앱_이름
```

- 앱 제거하기:

```bash
dokku apps:destroy 앱_이름
```

- 플러그인 설치하기:

```bash
dokku plugin:install 전체_폴더_경로
```

- 앱에 데이터베이스 연결하기:

```bash
dokku db:link 데이터베이스_이름 앱_이름
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Proscream](mailto:proscream@naver.com) | dokku: Add Korean Translation (#3836) | 2020-02-05T17:17:55 | [6dbae63b1616](https://github.com/tldr-pages/tldr/commit/6dbae63b16163dc90422bccc7c7294e135f9360d)

