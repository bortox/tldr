---
author: ['Proscream', 'Marco Bonelli']
date: 1574435377
title: "cake"
description: "cake, CakePHP 프레임 워크용 명령어 라인 프로세서."
categories: "common"
---
> 더 많은 정보: <https://cakephp.org>.

- 현재 앱 및 사용 가능한 명령어에 대한 기본 정보 표시:

```bash
cake
```

- 사용 가능한 경로 리스트 표시:

```bash
cake routes
```

- 구성 캐시 지우기:

```bash
cake cache clear_all
```

- 메타데이터 캐시 구축:

```bash
cake schema_cache build --connection 연결할것
```

- 메타데이터 캐시 지우기:

```bash
cake schema_cache clear
```

- 단일 캐시 테이블 지우기:

```bash
cake schema_cache clear 테이블_이름
```

- 개발 웹 서버 시작 (포트 기본값 8765):

```bash
cake server
```

- REPL 대화형 쉘 인스턴스 시작:

```bash
cake console
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages(bzip2 to cake) : Add Korean Translation (#3579) | 2019-11-19T18:17:05 | [0d6ef290eb21](https://github.com/tldr-pages/tldr/commit/0d6ef290eb21a44bf9d8275802396b9fae12acd8)

