---
author: ['Schneider', 'lch7167', 'Noy', 'bl-ue']
date: 1631909240
title: "black"
description: "black, Python 자동 코드 formatter."
categories: "common"
---
> 더 많은 정보: <https://github.com/psf/black>.

- 파일 또는 전체 디렉토리의 자동 포맷:

```bash
black 파일_또는_디렉토리/의/경로
```

- 전달된 코드를 문자열로 포맷:

```bash
black -c 파일_또는_디렉토리/의/경로
```

- 표준 출력시 각 파일에 대해 diff 출력:

```bash
black --diff 파일_또는_디렉토리/의/경로
```

- 파일을 다시 쓰지 않고 상태 반환:

```bash
black --check 파일_또는_디렉토리/의/경로
```

- 파일 또는 디렉토리가 stderr에 배타적 오류 메시지를 발생시키는 자동 포맷:

```bash
black --quiet 파일_또는_디렉토리/의/경로
```

- 작은 따옴표를 큰 따옴표로 바꾸지 않고 파일 또는 디렉토리 자동 서식 지정(채택 도우미, 새 프로젝트에 사용하지 마세요):

```bash
black --skip-string-normalization 파일_또는_디렉토리/의/경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Noy](mailto:noah.altunian@motorolasolutions.com) | black: add --skip-string-normalization example (#6517) | 2021-09-17T22:07:20 | [153c6d13bc4c](https://github.com/tldr-pages/tldr/commit/153c6d13bc4c485df335860b434b5635d2485791)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

