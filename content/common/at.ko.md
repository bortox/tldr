---
author: ['Proscream', 'bl-ue', 'marchersimon']
date: 1659075216
title: "at, TLDR Pages"
description: "at, 명령 실행 후 한 번 실행합니다."
categories: "common"
---
> 서비스 AD(또는 ATRUN)는 실제 실행을 위해 실행되어야 합니다.

> 더 많은 정보: <https://manned.org/at>.

- 표준 입력에서 명령을 5분 내에 실행(작업이 끝나면 `Ctrl + D` 를 누르세요):

```bash
at now + 5 minutes
```

- 오전 10시에 표준 입력에서 명령을 실행하십시오:

```bash
echo "./make_db_backup.sh" | at 1000
```

- 다음 주 화요일에 주어진 파일에서 명령을 실행하십시오:

```bash
at -f 경로/파일명 9:30 PM Tue
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Proscream](mailto:proscream@naver.com) | multiple pages(asciinema to atoum) : Add Korean Translation (#3556) | 2019-11-26T19:49:10 | [3c656248966b](https://github.com/tldr-pages/tldr/commit/3c656248966bd2da299e8964d96ef6df09d8ed0f)

