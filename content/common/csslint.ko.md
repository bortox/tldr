---
author: ['Marco Bonelli', 'dmakth', 'bl-ue']
date: 1612369364
title: "csslint, TLDR Pages"
description: "csslint, CSS 코드용 린터."
categories: "common"
---
> 더 많은 정보: <https://github.com/CSSLint/csslint/wiki/Command-line-interface>.

- 하나의 CSS 파일을 린트:

```bash
csslint 파일.css
```

- 여러개의 CSS 파일을 린트:

```bash
csslint 파일1.css 파일2.css 파일3.css
```

- 가능한 모든 스타일 규칙 나열:

```bash
csslint --list-rules
```

- 특정 규칙을 오류로 지정 (종료 코드가 0이아닌 결과로 도출):

```bash
csslint --errors=에러,보편적-선택자,임포트 파일.css
```

- 특정 규칙을 경고로 지정:

```bash
csslint --warnings=박스-사이징,선택자-최대값,플롯 파일.css
```

- 완전히 무시할 특정 규칙을 지정:

```bash
csslint --ignore=ids,규칙-수,속기 파일.css
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | multiple pages: Add Korean Translation (#3584) | 2019-11-19T19:48:15 | [3e86af347248](https://github.com/tldr-pages/tldr/commit/3e86af347248ab317195c5106a2aee9d8897c9ea)

