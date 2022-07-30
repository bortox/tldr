---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1610462196
title: "browser-sync"
description: "browser-sync, 파일 변경에 따라 브라우저를 업데이트 하는 로컬 웹 서버 시작."
categories: "common"
---
> 더 많은 정보: <https://browsersync.io/docs/command-line>.

- 특정 디렉토리로부터 서버 시작:

```bash
browser-sync start --server 디렉토리/의/경로 --files 디렉토리/의/경로
```

- 로컬 디렉토리에서 서버 시작, 일부 디렉토리에서 모든 css파일 확인:

```bash
browser-sync start --server --files '디렉토리/의/경로/*.css'
```

- 구성 파일 생성:

```bash
browser-sync init
```

- 구성 파일에서 브라우저 동기화 시작:

```bash
browser-sync start --config config_파일
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

