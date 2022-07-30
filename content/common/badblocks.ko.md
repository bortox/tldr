---
author: ['lch7167', 'bl-ue', 'Marco Bonelli', 'marchersimon']
date: 1618756407
title: "badblocks"
description: "badblocks, 불량 블록이 있는지 장치를 검사하십시오."
categories: "common"
---
> 불량 블록을 사용하면 파티션 테이블을 포함하여 디스크의 모든 데이터를 지우는 등의 파괴적인 작업이 발생할 수 있습니다.

> 더 많은 정보: <https://manned.org/badblocks>.

- 비파괴 읽기 전용 테스트를 사용하여 디스크에서 불량 블록을 검사:

```bash
sudo badblocks /dev/sda
```

- 비파괴 읽기-쓰기 테스트로 마운트되지 않은 디스크에서 불량 블록이 있는지 검사:

```bash
sudo badblocks -n /dev/sda
```

- 파괴 쓰기 테스트로 마운드되지 않은 디스크에서 불량 블록이 있는지 검사:

```bash
sudo badblocks -w /dev/sda
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: fix link | 2021-04-18T16:33:27 | [9dcaa79cdbd6](https://github.com/tldr-pages/tldr/commit/9dcaa79cdbd60c09b0c06e17d2c7e689a3ab4126)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: add link | 2021-04-18T16:33:27 | [962f1bc5ed08](https://github.com/tldr-pages/tldr/commit/962f1bc5ed08dfe6e4cdb2541bc0fa805e91af71)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

