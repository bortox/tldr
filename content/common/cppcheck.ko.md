---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "cppcheck, TLDR Pages"
description: "cppcheck, C/C++ 코드를 위한 정적 분석 도구."
categories: "common"
---
> 구문 오류 대신 컴파일러가 일반적으로 감지하지 못하는 버그 유형에 중점을 둠.

> 더 많은 정보: <http://cppcheck.sourceforge.net>.

- 화면에 진행률을 표시하고 오류 메시지를 파일에 로깅하여 현재 디렉토리를 반복적으로 확인:

```bash
cppcheck . 2> cppcheck.log
```

- 주어진 디렉토리를 재귀적으로 확인하고, 진행 메시지를 출력하지 않음:

```bash
cppcheck --quiet 디렉토리/의/경로
```

- 수행 할 테스트를 지정하여 주어진 파일을 확인(기본적으로 오류만 표시됨):

```bash
cppcheck --enable=error|warning|style|performance|portability|information|all file.cpp/의/경로
```

- 사용 가능한 테스트 목록:

```bash
cppcheck --errorlist
```

- 특정 테스트를 무시하고 주어진 파일을 확인:

```bash
cppcheck --suppress=test_id1 --suppress=test_id2 file.cpp/의/경로
```

- 현재 디렉토리를 확인하여 외부에 있는 include 파일의 경로를 제공(예 : 외부 라이브러리):

```bash
cppcheck -I include/디렉토리_1 -I include/디렉토리_2 .
```

- Microsoft Visual Studio 프로젝트 (`*.vcxproj`) 또는 솔루션 (`*.sln`)을 확인:

```bash
cppcheck --project=project.sln/의/경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cp to cradle-elastic): add korean translation (#3607) | 2019-11-26T10:52:56 | [bd07a73beb01](https://github.com/tldr-pages/tldr/commit/bd07a73beb0168939d441cd008f17b80775a9ead)

