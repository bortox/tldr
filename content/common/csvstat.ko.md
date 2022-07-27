---
author: ['dmakth']
date: 1574410217
title: "csvstat, TLDR Pages"
description: "csvstat, csvkit에 포함된 CSV 파일의 모든 열에 대한 설명 통계 출력."
categories: "common"
---
> 더 많은 정보: <https://csvkit.readthedocs.io/en/latest/scripts/csvstat.html>.

- 모든 열에 대한 정보 출력:

```bash
csvstat 데이터.csv
```

- 2열 , 4열의 모든 정보 출력:

```bash
csvstat -c 2,4 데이터.csv
```

- 모든 열의 합계 출력:

```bash
csvstat --sum data.csv
```

- 3열에 대한 최대값 길이 출력:

```bash
csvstat -c 3 --len 데이터.csv
```

- "이름" 열에 고유 값의 수 출력:

```bash
csvstat -c 이름 --unique 데이터.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

