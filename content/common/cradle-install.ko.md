---
author: ['bl-ue']
date: 1610858159
title: "cradle install"
description: "cradle install, Cradle PHP 프레임워크 구성 요소를 설치."
categories: "common"
---
> 더 많은 정보: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#install>.

- Cradle의 구성요소 설치 (유저는 자세한 내용을 묻는 메시지를 받음):

```bash
cradle install
```

- 파일을 강제로 덮어 쓰기:

```bash
cradle install --force
```

- 실행중인 SQL 마이그레이션 건너 뛰기:

```bash
cradle install --skip-sql
```

- 실행중인 패키지 업데이트 건너 뛰기:

```bash
cradle install --skip-versioning
```

- 특정 데이터베이스 세부 사항 사용:

```bash
cradle install -h 호스트명 -u 유저명 -p 비밀번호
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | cradle-install: fix page name | 2021-01-17T05:35:59 | [ed45d6527e21](https://github.com/tldr-pages/tldr/commit/ed45d6527e21030fc4cf86367f70c3d62d7f99f0)

