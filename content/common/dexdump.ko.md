---
author: ['Axel Navarro', 'Proscream', 'marchersimon']
date: 1625253777
title: "dexdump"
description: "dexdump, 안드로이드 DEX 파일들에 대한 정보 출력."
categories: "common"
---
> 더 많은 정보: <https://manned.org/dexdump>.

- APK 파일으로부터 클래스들과 메서드들 추출:

```bash
dexdump 경로/파일명.apk
```

- APK 파일에 포함된 DEX 파일들의 헤더 정보 출력:

```bash
dexdump -f 경로/파일명.apk
```

- 실행가능한 섹션의 분해된 결과 출력:

```bash
dexdump -d 경로/파일명.apk
```

- 파일로 결과 출력:

```bash
dexdump -o 경로/파일명 경로/파일명.apk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Axel Navarro](mailto:navarroaxel@gmail.com) | dexdump: add more information link (#5142) | 2021-01-15T18:24:33 | [b112894a976a](https://github.com/tldr-pages/tldr/commit/b112894a976a301565f4784165376e14585fa740)
[Proscream](mailto:proscream@naver.com) | dexdump : Add Korean Translation (#3666) | 2019-12-21T00:09:51 | [1e4c44ab18fd](https://github.com/tldr-pages/tldr/commit/1e4c44ab18fdc49f66a468b3ba7cd0c1ef3e0446)

