---
author: ['Schneider', 'Proscream', 'Seth Falco', 'bl-ue']
date: 1648358715
title: "assimp, TLDR Pages"
description: "assimp, Open Asset Import Library 위한 Command-line 클라이언트."
categories: "common"
---
> 40 +3D 파일 형식을 지원하고 몇 개의 유명한 3D포맷으로 내보낼 수 있습니다.

> 더 많은 정보: <http://www.assimp.org/>.

- 지원되는 모든 가져오기 형식을 나열:

```bash
assimp listext
```

- 지원되는 모든 내보내기 형식 나열:

```bash
assimp listexport
```

- 기본 매개 변수를 사용하여 파일을 지원되는 출력 형식 중 하나로 변환:

```bash
assimp export 입력_파일명.stl 출력_파일명.obj
```

- 사용자 정의 매개 변수 (Assimp의 소스 코드 목록에서 dox_cmd.h 파일 사용 가능한 매개 변수)를 사용하여 파일을 변환:

```bash
assimp export 입력_파일명.stl 출력_파일명.obj 매개변수
```

- 3D 파일의 내용을 요약하여 표시:

```bash
assimp info 경로/파일명
```

- 지원되는 모든 하위 명령 ("Verb")을 나열:

```bash
assimp help
```

- 특정 하위 명령에 대한 도움말 얻기 (예 : 특정 하위 명령에 특정 매개 변수):

```bash
assimp 하위명령어 --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Proscream](mailto:proscream@naver.com) | multiple pages(asciinema to atoum) : Add Korean Translation (#3556) | 2019-11-26T19:49:10 | [3c656248966b](https://github.com/tldr-pages/tldr/commit/3c656248966bd2da299e8964d96ef6df09d8ed0f)

