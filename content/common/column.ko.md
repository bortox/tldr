---
author: ['Schneider', 'JJByun', 'marchersimon']
date: 1618756407
title: "column"
description: "column, 표준 입력 또는 파일을 여러 열로 포맷 설정."
categories: "common"
---
> 행 앞에 열이 채워짐; 기본 구분 기호는 공백입니다.

> 더 많은 정보: <https://manned.org/column>.

- 30자 폭 디스플레이의 형식 출력으로 포맷 정하기:

```bash
printf "header1 header2\nbar foo\n" | column --output-width 30
```

- 열 자동 분할 및 자동 정렬을 표 형식으로 분할:

```bash
printf "header1 header2\nbar foo\n" | column --table
```

- -t 옵션(예: "", csv)에 대한 열 구분 기호 문자를 지정; 기본값은 공백입니다:

```bash
printf "header1,header2\nbar,foo\n" | column --table --separator ,
```

- 열을 채우기 전에 행 채우기:

```bash
printf "header1\nbar\nfoobar\n" | column --output-width 30 --fillrows
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | column: add link | 2021-04-18T16:33:27 | [010ec036106c](https://github.com/tldr-pages/tldr/commit/010ec036106ce5c68aa2a9416ad819d1014178da)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[JJByun](mailto:jd0909@naver.com) | merge mutiple pages(cmake to command) : Add Korean Translation (#3595) * korean translation cmake cmark cmp code coffee column comm [...] | 2019-11-22T16:25:18 | [61f5b847208b](https://github.com/tldr-pages/tldr/commit/61f5b847208bf1994b04849aaa5d16948f1716b5)

