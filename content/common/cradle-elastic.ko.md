---
author: ['bl-ue']
date: 1610858159
title: "cradle elastic, TLDR Pages"
description: "cradle elastic, Cradle 인스턴스의 ElasticSearch 인스턴스 관리."
categories: "common"
---
> 더 많은 정보: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#elastic>.

- ElasticSearch 색인 자르기:

```bash
cradle elastic flush
```

- 특정 패키지에 대한 ElasticSearch 색인 자르기:

```bash
cradle elastic flush 패키지_명
```

- ElasticSearch 스키마 제출:

```bash
cradle elastic map
```

- 특정 패키지에 대한 ElasticSearch 스키마 제출:

```bash
cradle elastic map 패키지_명
```

- 모든 패키지에 대한 ElasticSearch 색인 채우기:

```bash
cradle elastic populate
```

- 특정 패키지에 대한 ElasticSearch 색인 채우기:

```bash
cradle elastic populate 패키지_명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | cradle-elastic: fix page name | 2021-01-17T05:35:59 | [e8e2ec242f95](https://github.com/tldr-pages/tldr/commit/e8e2ec242f95362df00d0f89dfa78c1d568af04e)

