---
author: ['dmakth']
date: 1574410217
title: "csvsort, TLDR Pages"
description: "csvsort, csvkit에 포함된 CSV 파일을 정렬."
categories: "common"
---
> 더 많은 정보: <https://csvkit.readthedocs.io/en/latest/scripts/csvsort.html>.

- CSV 파일을 9열을 기준으로 정렬:

```bash
csvsort -c 9 데이터.csv
```

- CSV 파일을 "이름" 열에 따라 내림차순으로 정렬:

```bash
csvsort -r -c 이름 데이터.csv
```

- CSV 파일을 2열, 4열을 기준으로 정렬:

```bash
csvsort -c 2,4 데이터.csv
```

- 데이터 형식과 관계 없이 CSV 파일 정렬:

```bash
csvsort --no-inference -c 열 데이터.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

