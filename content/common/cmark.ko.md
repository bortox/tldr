---
author: ['JJByun', 'bl-ue', 'Marco Bonelli']
date: 1621541621
title: "cmark"
description: "cmark, CommonMark Markdown 텍스트를 다른 텍스트 형식으로 변환합니다."
categories: "common"
---
> 더 많은 정보: <https://github.com/commonmark/cmark>.

- CommonMark Markdown 파일을 HTML 파일로 렌더링합니다:

```bash
cmark --to html 파일명.md
```

- 데이터를 표준 입력에서 라텍스로 변환:

```bash
cmark --to latex
```

- 직선 따옴표를 스마트 따옴표로 변환:

```bash
cmark --smart --to html 파일명.md
```

- UTF-8 문자들을 검증:

```bash
cmark --validate-utf8 파일명.md
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add missing trailing newline to some Korean pages (#3633) | 2019-11-28T22:16:38 | [53af408ce5f2](https://github.com/tldr-pages/tldr/commit/53af408ce5f2cd186e88d32b54203109e890486c)
[JJByun](mailto:jd0909@naver.com) | merge mutiple pages(cmake to command) : Add Korean Translation (#3595) * korean translation cmake cmark cmp code coffee column comm [...] | 2019-11-22T16:25:18 | [61f5b847208b](https://github.com/tldr-pages/tldr/commit/61f5b847208bf1994b04849aaa5d16948f1716b5)

