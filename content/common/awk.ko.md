---
author: ['Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'lch7167', 'bl-ue']
date: 1612112718
title: "awk"
description: "awk, 파일 작업을 위한 다목적 프로그래밍 언어."
categories: "common"
---
> 더 많은 정보: <https://github.com/onetrueawk/awk>.

- 공백으로 구분 된 파일의 다섯 번째 열 (일명 필드)를 출력하기:

```bash
awk '{print $5}' filename
```

- 공백으로 구분 된 파일에서 `foo`을 포함한 두 번째 열 출력하기:

```bash
awk '/foo/ {print $2}' filename
```

- 공백이 아닌 쉼표를 필드 구분 기호로 사용한 파일에서 각 줄의 마지막 열을 출력하기:

```bash
awk -F ',' '{print $NF}' filename
```

- 파일의 첫 번째 열에 있는 값을 더하고 합계를 출력:

```bash
awk '{s+=$1} END {print s}' filename
```

- 첫 번째 열에 있는 값을 더하고 값들을 출력하고 합계를 출력:

```bash
awk '{s+=$1; print $1} END {print "--------"; print s}' filename
```

- 첫 번째 줄부터 시작하여 세 번째 줄까지 모두 출력:

```bash
awk 'NR%3==1' filename
```

- 세 번째 열부터 시작하여 모든 값을 출력:

```bash
awk '{ s = ""; for (i=3; i <= NF; i++) s = s $i " "; print s }'
```

- 조건에 따라 다른 값을 출력:

```bash
awk '{if ($1 == "foo") print "Exact match foo"; else if ($1 ~ "bar") print "Partial match bar"; else print "Baz"}'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

