---
author: ['Dario Vladović', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'lch7167', 'bl-ue', 'marchersimon']
date: 1617292466
title: "b2sum"
description: "b2sum, BLACK2 암호화 체크섬을 계산하십시오."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/b2sum>.

- 파일의 BLACKE2 체크섬 계산:

```bash
b2sum filename1
```

- 여러 파일의 BLACKE2 체크섬 계산:

```bash
b2sum filename1 filename2
```

- BLAKE2 합계 파일 및 파일 이름을 읽고 모든 파일에 일치하는 체크섬이 있는지 확인:

```bash
b2sum -c filename.b2
```

- stdin에서 BLACK2 체크섬 계산:

```bash
somecommand | b2sum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | b2sum: change more information link (#5563) | 2021-03-30T12:25:10 | [572bb893c6d2](https://github.com/tldr-pages/tldr/commit/572bb893c6d23a07c13c09b6dd61a954a1950381)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

