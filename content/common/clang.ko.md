---
author: ['Schneider', 'JJByun', 'bl-ue']
date: 1617493464
title: "clang, TLDR Pages"
description: "clang, C, C++ 그리고 Objective-C 소스 파일을 컴파일합니다. GCC의 드롭인 대체로 사용할 수 있습니다."
categories: "common"
---
> 더 많은 정보: <https://clang.llvm.org/docs/ClangCommandLineReference.html>.

- 실행 가능한 바이너리 파일로 소스 코드를 컴파일합니다:

```bash
clang 입력_소스.c -o 출력_실행가능파일
```

- 모든 에러와 경고 메시지를 출력하도록 활성화합니다:

```bash
clang 입력_소스.c -Wall -o 출력_실행가능파일
```

- 소스 파일과 다른 경로에 있는 라이브러리를 포함합니다:

```bash
clang 입력_소스.c -o 출력_실행가능파일 -I헤더_경로 -L라이브러리_경로 -l라이브러리명
```

- 소스 코드를 LLVM Intermediate Representation(IR)로 컴파일 합니다:

```bash
clang -S -emit-llvm 파일.c -o 파일.ll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[JJByun](mailto:jd0909@naver.com) | multiple pages : Add Korean Translation (#3583) * Translation-ko chsh.md cksum.md clamscan.md clang.md clear.md clementine.md cloc.md [...] | 2019-11-24T20:33:52 | [1c78b9e10694](https://github.com/tldr-pages/tldr/commit/1c78b9e10694d378aa40b6236450be14a3ef6a21)

