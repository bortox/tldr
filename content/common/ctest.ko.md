---
author: ['dmakth']
date: 1574410217
title: "ctest, TLDR Pages"
description: "ctest, CMake 테스트 드라이버 프로그램."
categories: "common"
---
> 더 많은 정보: <https://gitlab.kitware.com/cmake/community/wikis/doc/ctest/Testing-With-CTest>.

- CMake 프로젝트에 정의된 모든 테스트를 실행하며 , 한번에 4개의 작업을 병렬 실행:

```bash
ctest -j4 --output-on-failure
```

- 사용 가능한 테스트 목록 표시:

```bash
ctest -N
```

- 이름을 기준으로 단일 테스트를 실행하거나 정규식을 기준으로 필터링:

```bash
ctest --output-on-failure -R '^테스트명$'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

