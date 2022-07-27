---
author: ['Dario Vladović', 'bl-ue', 'marchersimon', 'Proscream']
date: 1617292466
title: "chown, TLDR Pages"
description: "chown, 파일과 디렉토리의 사용자 및 그룹 소유권을 변경."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/chown>.

- 파일/디렉토리의 소유 사용자 변경:

```bash
chown 사용자 경로/파일명_또는_디렉토리명
```

- 파일/디렉토리의 소유 사용자 및 그룹 변경:

```bash
chown 사용자:그룹 경로/파일명_또는_디렉토리명
```

- 디렉토리 소유자와 그 내용을 재귀적으로 변경:

```bash
chown -R 사용자 경로/디렉토리명
```

- 심볼릭 링크의 소유자 변경:

```bash
chown -h 사용자 경로/심볼릭_링크
```

- 참조 파일과 일치하도록 파일/디렉토리 소유자 변경:

```bash
chown --reference=경로/참조_파일명 경로/파일명_또는_디렉토리명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Korean pages: fix (valid) tldr-lint errors (#5376) | 2021-03-08T20:59:31 | [4061936c0ca2](https://github.com/tldr-pages/tldr/commit/4061936c0ca2344cc9beb92218dbf02e583fee83)
[Proscream](mailto:proscream@naver.com) | Multiple pages(chisel to chroot) : Add Korean Translation (#3586) | 2019-11-19T18:22:39 | [bfbe15c8e437](https://github.com/tldr-pages/tldr/commit/bfbe15c8e4378a26e43b9dfe6f4ce65e2222df02)

