---
author: ['Marco Bonelli', 'dmakth']
date: 1574435377
title: "csc, TLDR Pages"
description: "csc, 마이크로 소프트 사의 C# 컴파일러."
categories: "common"
---
> 더 많은 정보: <https://docs.microsoft.com/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe>.

- 하나 이상의 C# 파일을 CIL 실행파일로 컴파일:

```bash
csc 경로/입력파일_a.cs 경로/입력파일_b.cs
```

- 출력 파일 이름 지정:

```bash
csc /out:경로/파일명 경로/입력파일.cs
```

- 실행 파일 대신 '.dll' 라이브러리로 컴파일:

```bash
csc /target:library 경로/입력파일.cs
```

- 다른 어셈블리 참조:

```bash
csc /reference:경로/라이브러리.dll 경로/입력파일.cs
```

- 리소스 포함:

```bash
csc /resource:경로/리소스파일 경로/입력파일.cs
```

- XML 문서 자동 생성:

```bash
csc /doc:경로/출력파일.xml 경로/입력파일.cs
```

- 아이콘 지정:

```bash
csc /win32icon:경로/아이콘.ico 경로/입력파일.cs
```

- 키 파일을 사용하여 결과 어셈블리의 이름 지정:

```bash
csc /keyfile:경로/키파일 경로/입력파일.cs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | multiple pages: Add Korean Translation (#3584) | 2019-11-19T19:48:15 | [3e86af347248](https://github.com/tldr-pages/tldr/commit/3e86af347248ab317195c5106a2aee9d8897c9ea)

