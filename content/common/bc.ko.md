---
author: ['lch7167', 'bl-ue', 'Marco Bonelli', 'marchersimon']
date: 1659075216
title: "bc"
description: "bc, 계산기의 기능을 수행합니다."
categories: "common"
---
> 더 많은 정보: <https://manned.org/man/bc.1>.

- 표준 Math 라이브러리를 사용한 대화형 모드에서 계산기 실행하기:

```bash
bc -l
```

- 계산 결과 표현법:

```bash
bc <<< "(1 + 2) * 2 ^ 2"
```

- 계산 및 표현되는 소수 자릿수를 10으로 지정하기:

```bash
bc <<< "scale=10; 5 / 3"
```

- mathlib를 사용하여 sin 및 cosine의 계산식 표현하기:

```bash
bc -l <<< "s(1) + c(1)"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | bc: add link | 2021-04-18T16:33:27 | [2c7348ccdd6b](https://github.com/tldr-pages/tldr/commit/2c7348ccdd6bc47e877d760a180c8cd685d9a4e8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

