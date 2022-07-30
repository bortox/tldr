---
author: ['Proscream', 'Marco Bonelli']
date: 1574435377
title: "ag"
description: "ag, The Silver Searcher."
categories: "common"
---
> ack과 비슷하지만, 더 빠르다.

> 더 많은 정보: <https://github.com/ggreer/the_silver_searcher>.

- "foo"를 포함하고 있는 파일들을 찾고, 내용에서 일치하는 행을 출력:

```bash
ag foo
```

- 특정 디렉토리에서 "foo"를 포함하고 있는 파일 찾기:

```bash
ag foo 경로/디렉토리명
```

- "foo"를 포함하고 있는 파일을 찾되, 파일 이름만 나열:

```bash
ag -l foo
```

- "FOO"를 포함하고 있는 파일들을 사례별로 찾고, 전체 라인이 아닌 일치 라인만 인쇄:

```bash
ag -i -o FOO
```

- "bar" 제목과 일치하는 파일에서 "foo" 찾기:

```bash
ag foo -G bar
```

- 내용이 정규식과 일치하는 파일 찾기:

```bash
ag '^ba(r|z)$'
```

- 이름이 "foo"와 일치하는 파일 찾기:

```bash
ag -g foo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

