---
author: ['dmakth', 'Dario Vladović', 'Mikey Garcia', 'bl-ue', 'marchersimon']
date: 1621528570
title: "date, TLDR Pages"
description: "date, 시스템 날짜 설정 및 표시."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/date>.

- 기본 로컬 형식을 사용하여 현재 날짜 표시:

```bash
date +"%c"
```

- 현재 날짜를 UTC 및 ISO 8601 형식으로 표시:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- 현재 날짜를 Unix 타임스탬프로 표시 (Unix epoch 이후 몇 초):

```bash
date +%s
```

- 기본 형식을 사용하여 특정 날짜 표시(Unix 타임스탬프로 표시):

```bash
date -d @1473305798
```

- 특정 날짜를 Unix 타임스탬프 형식으로 변환:

```bash
date -d "2018-09-01 00:00" +%s --utc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Revert "date: fix typo (#4069)" (#5997) | 2021-05-20T18:36:10 | [33b5fcd7bdc9](https://github.com/tldr-pages/tldr/commit/33b5fcd7bdc9e3e169e3a3c5c8b767dcb05b770e)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | date: add more information link (#5603) | 2021-03-30T15:50:57 | [b98c0e84a5b2](https://github.com/tldr-pages/tldr/commit/b98c0e84a5b2228add4fe1831fd2eb151c14bca1)
[Mikey Garcia](mailto:gikeymarcia@gmail.com) | date: fix typo (#4069) | 2020-05-27T05:46:20 | [e0151803205b](https://github.com/tldr-pages/tldr/commit/e0151803205bb7efa1e2222a979580dbcfc19589)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

