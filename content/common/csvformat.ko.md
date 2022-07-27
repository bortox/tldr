---
author: ['Marco Bonelli', 'dmakth']
date: 1574435377
title: "csvformat, TLDR Pages"
description: "csvformat, csvkit에 포함된 CSV 파일을 사용자 정의 출력으로 변환."
categories: "common"
---
> 더 많은 정보: <https://csvkit.readthedocs.io/en/latest/scripts/csvformat.html>.

- 탭으로 구분된 파일(TSV)로 변환:

```bash
csvformat -T 데이터.csv
```

- 구분자를 사용자 지정 문자로 변환:

```bash
csvformat -D "사용자_지정_문자" 데이터.csv
```

- 라인의 끝을 캐리지 리턴 (^M) + 라인 바꿈으로 변환:

```bash
csvformat -M "\r\n" 데이터.csv
```

- 인용문 사용 최소화:

```bash
csvformat -U 0 데이터.csv
```

- 인용문 사용 최대화:

```bash
csvformat -U 1 데이터.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | multiple pages: Add Korean Translation (#3584) | 2019-11-19T19:48:15 | [3e86af347248](https://github.com/tldr-pages/tldr/commit/3e86af347248ab317195c5106a2aee9d8897c9ea)

