---
author: ['Schneider', 'JJByun', 'marchersimon']
date: 1633112881
title: "cmake"
description: "cmake, 빌드 시스템을 생성하는 크로스 플랫폼으로 선택한 시스템에 따라 Makefiles, Visual Studio 프로젝트 또는 기타를 생성합니다."
categories: "common"
---
> 더 많은 정보: <https://cmake.org/cmake/help/latest/manual/cmake.1.html>.

- 작성 파일을 생성하고 이를 사용하여 원본과 동일한 디렉토리에서 프로젝트를 컴파일합니다:

```bash
cmake && make
```

- Makefile을 생성하고 이를 사용하여 별도의 "빌드" 디렉토리(소스 외 빌드)에 프로젝트를 컴파일합니다:

```bash
cmake -H. -B빌드 && make -C 빌드
```

- 대화형 모드로 cmake를 실행 (기본값을 사용하는 대신 각 변수에 대해 요청합니다):

```bash
cmake -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[JJByun](mailto:jd0909@naver.com) | merge mutiple pages(cmake to command) : Add Korean Translation (#3595) * korean translation cmake cmark cmp code coffee column comm [...] | 2019-11-22T16:25:18 | [61f5b847208b](https://github.com/tldr-pages/tldr/commit/61f5b847208bf1994b04849aaa5d16948f1716b5)

