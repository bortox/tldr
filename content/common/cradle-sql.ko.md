---
author: ['bl-ue']
date: 1610858159
title: "cradle sql, TLDR Pages"
description: "cradle sql, Cradle SQL 데이터베이스 관리."
categories: "common"
---
> 더 많은 정보: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#sql>.

- 데이터베이스 스키마 재구축:

```bash
cradle sql build
```

- 특정 패키지에 대한 데이터베이스 스키마 재구축:

```bash
cradle sql build 패키지_명
```

- 전체 데이터베이스 비우기:

```bash
cradle sql flush
```

- 특정 패키지에 대한 데이터베이스 테이블 비우기:

```bash
cradle sql flush 패키지_명
```

- 모든 패키지에 대한 테이블 채우기:

```bash
cradle sql populate
```

- 특정 패키지에 대한 테이블 채우기:

```bash
cradle sql populate 패키지_명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | cradle-sql: fix page name | 2021-01-17T05:35:59 | [37e183397c4e](https://github.com/tldr-pages/tldr/commit/37e183397c4ed5db4e97747e26940f98da40f6a2)

