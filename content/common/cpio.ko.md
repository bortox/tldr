---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "cpio"
description: "cpio, 아카이브 안팎으로 파일을 복사. cpio의 custom binary, old ASCII, new ASCII, crc, HPUX binary, HPUX old ASCII, old tar, POSIX.1 tar.와 같은 아카이브 형식을 지원함."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/cpio>.

- 표준 입력에서 파일 이름 목록을 가져와서 cpio의 이진 형식으로 아카이브[o]에 추가:

```bash
echo "파일1 파일2 파일3" | cpio -o > archive.cpio
```

- 디렉토리의 모든 파일과 디렉토리를 복사하여 [v]상세모드에서 아카이브[o]에 추가:

```bash
find 디렉토리/의/경로 | cpio -ov > archive.cpio
```

- 아카이브에 모든 파일을 [i]선택하여 필요한 경우 [v]상세모드로 [d]디렉토리를 생성:

```bash
cpio -idv < archive.cpio
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cp to cradle-elastic): add korean translation (#3607) | 2019-11-26T10:52:56 | [bd07a73beb01](https://github.com/tldr-pages/tldr/commit/bd07a73beb0168939d441cd008f17b80775a9ead)

