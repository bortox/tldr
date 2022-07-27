---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1610462196
title: "bundle, TLDR Pages"
description: "bundle, Ruby 프로그래밍 언어의 종속성 관리자."
categories: "common"
---
> 더 많은 정보: <https://bundler.io/man/bundle.1.html>.

- 작업 디렉토리에 있는 `Gemfile`에 정의된 모든 gem을 설치:

```bash
bundle install
```

- `Gemfile` 에 정의된 규칙에 따라 모든 gem을 업데이트 하고 `Gemfile.lock`을 재생성:

```bash
bundle update
```

- `Gemfile`에 정의된 특정 gem을 업데이트:

```bash
bundle update --source gem명
```

- 새로운 gem의 스켈레톤 생성:

```bash
bundle gem gem명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

