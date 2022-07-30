---
author: ['dmakth', 'Guido Lena Cota', 'Marco Bonelli']
date: 1601832818
title: "csvgrep"
description: "csvgrep, csvkit에 포함된 CSV행의 문자열 및 패턴 매칭 필터링."
categories: "common"
---
> 더 많은 정보: <https://csvkit.readthedocs.io/en/latest/scripts/csvgrep.html>.

- 1 열에 특정 문자열이 있는 행 찾기:

```bash
csvgrep -c 1 -m 찾을_문자열 데이터.csv
```

- 3열 또는 4열에서 특정 정규식 패턴과 일치하는 행 찾기:

```bash
csvgrep -c 3,4 -r 정규식_패턴 데이터.csv
```

- "이름" 열에서 "John Doe"가 포함되지 않는 행 찾기:

```bash
csvgrep -i -c 이름 -m "John Doe" 데이터.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | multiple pages: Add Korean Translation (#3584) | 2019-11-19T19:48:15 | [3e86af347248](https://github.com/tldr-pages/tldr/commit/3e86af347248ab317195c5106a2aee9d8897c9ea)

