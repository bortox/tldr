---
author: ['lch7167', 'bl-ue']
date: 1610731489
title: "bmaptool, TLDR Pages"
description: "bmaptool, 블록 맵을 지능적으로 생성 및 복사( `cp` 혹은 `dd`보다 빠른 속도)."
categories: "common"
---
> 더 많은 정보: <https://source.tizen.org/documentation/reference/bmaptool>.

- 이미지 파일에서 블록 맵 생성:

```bash
bmaptool create -o 블록맵.bmap 이미지 파일
```

- 이미지 파일을 sdb로 복사:

```bash
bmaptool copy --bmap 블록맵.bmap 이미지 파일 /dev/sdb
```

- 압축된 이미지 파일을 sdb로 복사:

```bash
bmaptool copy --bmap 블록맵.bmap 압축된 이미지 파일 /dev/sdb
```

- 블록맵을 사용하지 않고 이미지 파일을 sdb로 복사:

```bash
bmaptool copy --nobmap 이미지 파일 /dev/sdb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

