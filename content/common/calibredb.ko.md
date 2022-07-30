---
author: ['Proscream', 'Marco Bonelli']
date: 1574435377
title: "calibredb"
description: "calibredb, 전자책 데이터베이스를 조작하는 도구."
categories: "common"
---
> Calibre 전자책 라이브러리의 일부.

> 더 많은 정보: <https://manual.calibre-ebook.com/generated/en/calibredb.html>.

- 도서관의 전자책들을 추가 정보와 함께 리스트로 출력:

```bash
calibredb list
```

- 추가 정보를 표시하며 전자책 검색:

```bash
calibredb list --search 검색_용어
```

- 전자책의 ID만 검색:

```bash
calibredb search 검색_용어
```

- 라이브러리에 전자책 하나 이상 추가하기:

```bash
calibredb add 파일명1 파일명2 …
```

- 라이브러리에서 전자책을 하나 이상 제거하기. 전자책 ID 필요(위를 참조하시오):

```bash
calibredb remove id1 id2 …
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | Multiple pages(calibredb to case) : Add Korean Translation (#3582) | 2019-11-19T18:19:13 | [8181c0c27ef2](https://github.com/tldr-pages/tldr/commit/8181c0c27ef2d2f85fdb7c07a4a0f0e02bf5a4d3)

