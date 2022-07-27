---
author: ['Marco Bonelli', 'dmakth']
date: 1574435377
title: "csvcut, TLDR Pages"
description: "csvcut, 유닉스의 `cut` 명령어와 같이 CSV 파일 필터링 및 잘라내기, tabular 데이터 보존을 위해. csvkit에 포함된 CSV 파일만 해당."
categories: "common"
---
> 더 많은 정보: <https://csvkit.readthedocs.io/en/latest/scripts/csvcut.html>.

- 모든 열의 인덱스 및 이름 출력:

```bash
csvcut -n 데이터.csv
```

- 첫번째 및 세번째 열 출력:

```bash
csvcut -c 1,3 데이터.csv
```

- 네번째 열을 **제외한** 모든 열 출력:

```bash
csvcut -C 4 데이터.csv
```

- "id" 및 "first name" (이 순서대로) 열 출력:

```bash
csvcut -c id,"first name" 데이터.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | multiple pages: Add Korean Translation (#3584) | 2019-11-19T19:48:15 | [3e86af347248](https://github.com/tldr-pages/tldr/commit/3e86af347248ab317195c5106a2aee9d8897c9ea)

