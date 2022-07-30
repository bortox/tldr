---
author: ['bl-ue', 'marchersimon', 'Marco Bonelli', 'lch7167']
date: 1659075216
title: "batch, TLDR Pages"
description: "batch, 시스템 로드 레벨이 허가된 후, 명령을 실행하십시오. 실제로 실행하기 위해서는 atd (혹은 atrun) 를 실행해야합니다."
categories: "common"
---
> 더 많은 정보: <https://manned.org/batch>.

- 표준 입력에서 명령 실행하기 (완료 시 `Ctrl + D` 를 누릅니다):

```bash
batch
```

- 표준 입력에서의 명령 실행하기:

```bash
echo "./make_db_backup.sh" | batch
```

- 특정 파일에서 명령 실행하기:

```bash
batch -f path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

