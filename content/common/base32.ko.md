---
author: ['lch7167', 'Dario Vladović', 'Matthias Lübken', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1617292466
title: "base32, TLDR Pages"
description: "base32, 파일 또는 표준 입력을 Base32와 표준 출력으로 인코딩하거나 디코딩함."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/base32>.

- 파일 인코딩:

```bash
base32 filename
```

- 파일 디코딩:

```bash
base32 --decode filename
```

- stdin에서 인코딩:

```bash
somecommand | base32
```

- stdin에서 디코딩:

```bash
somecommand | base32 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | base32: add link (#5571) | 2021-03-30T09:11:31 | [30331c3d152d](https://github.com/tldr-pages/tldr/commit/30331c3d152d78ba495f78b7759f04b7bcd46f9f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Korean pages: fix (valid) tldr-lint errors (#5376) | 2021-03-08T20:59:31 | [4061936c0ca2](https://github.com/tldr-pages/tldr/commit/4061936c0ca2344cc9beb92218dbf02e583fee83)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

