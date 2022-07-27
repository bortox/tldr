---
author: ['marchersimon', 'Proscream']
date: 1633112881
title: "dep, TLDR Pages"
description: "dep, Go 프로젝트에서 종속성 관리를 위한 툴."
categories: "common"
---
> 더 많은 정보: <https://deployer.org>.

- 현재 디렉토리를 Go 프로젝트의 루트 디렉토리로 초기화:

```bash
dep init
```

- 누락된 종속성 설치(Gopkg.toml 과 .go 파일들 스캔):

```bash
dep ensure
```

- 프로젝트의 종속성의 상태 보고:

```bash
dep status
```

- 프로젝트에 종속성 추가:

```bash
dep ensure -add 패키지_url
```

- 모든 종속성들의 잠긴 버전 업데이트:

```bash
dep ensure -update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Proscream](mailto:proscream@naver.com) | dep : Add Korean Translation (#3660) | 2019-12-17T21:28:15 | [a5f91094dccc](https://github.com/tldr-pages/tldr/commit/a5f91094dccc99cd5afa2f87af1030c47e8c0a7a)

