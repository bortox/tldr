---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1615233571
title: "boot"
description: "boot, Clojure 프로그래밍 언어를 위한 빌드."
categories: "common"
---
> 더 많은 정보: <https://github.com/boot-clj/boot>.

- 프로젝트 혹은 독립으로 REPL 세션 시작:

```bash
boot repl
```

- 단일 "uberjar" 구축:

```bash
boot jar
```

- 명령어 안내:

```bash
boot cljs --help
```

- 템플릿을 기반으로 새로운 프로젝트에 대한 기반 생성:

```bash
boot --dependencies boot/new new --template 템플릿명 --name 프로젝트명
```

- 개발용 빌드 (부트/새 템플릿을 사용하는 경우):

```bash
boot dev
```

- 생산용 빌드 (부트/새 템플릿을 사용하는 경우):

```bash
boot prod
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Korean pages: fix (valid) tldr-lint errors (#5376) | 2021-03-08T20:59:31 | [4061936c0ca2](https://github.com/tldr-pages/tldr/commit/4061936c0ca2344cc9beb92218dbf02e583fee83)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

