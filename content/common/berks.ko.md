---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1610731489
title: "berks"
description: "berks, Chef 자세한 설명서 의존 관리자."
categories: "common"
---
> 더 많은 정보: <https://docs.chef.io/berkshelf.html>.

- 로컬 저장소에 자세한 설명서 종속성 설치:

```bash
berks install
```

- 특정 자세한 설명서와 그 종속성을 업데이트:

```bash
berks update 자세한 설명서
```

- 자세한 설명서를 Chef server에 업로드:

```bash
berks upload 자세한 설명서
```

- 자세한 설명서의 종속성 확인:

```bash
berks contingent 자세한 설명서
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

