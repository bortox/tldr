---
author: ['Schneider', 'lch7167', 'bl-ue', 'marchersimon']
date: 1633112881
title: "box, TLDR Pages"
description: "box, Phar의 빌드 및 관리를 위한 PHP 어플리케이션."
categories: "common"
---
> 더 많은 정보: <https://github.com/box-project/box>.

- 새 Phar 파일 작성:

```bash
box build
```

- 특정 구성 파일을 사용하여 새 Phar 파일 작성:

```bash
box build -c config/의/경로
```

- PHAR PHP 확장에 대한 정보 표시:

```bash
box info
```

- 특정 Phar 파일에 대한 정보 표시:

```bash
box info phar_파일/의/경로
```

- 현재 작업 디렉토리에서 처음으로 발견된 구성 파일 확인:

```bash
box validate
```

- 특정 Phar 파일의 서명 확인:

```bash
box verify phar_파일/의/경로
```

- 사용 가능한 모든 명령 및 옵션 표시:

```bash
box help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

