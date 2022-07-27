---
author: ['Dario Vladović', 'marchersimon', 'Proscream']
date: 1617292466
title: "df, TLDR Pages"
description: "df, 파일 시스템 디스크 공간 사용량에 대한 개요를 제공합니다."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/df>.

- 모든 파일 시스템들과 그들의 디스크 사용량 출력:

```bash
df
```

- 사람이 읽을 수 있는 형태로 모든 파일시스템들과 그들의 디스크 사용량 출력:

```bash
df -h
```

- 주어진 파일이나 디렉토리를 포함하는 파일 시스템과 그것의 디스크 사용량 출력:

```bash
df 경로/파일_혹은_디렉토리명
```

- 사용 가능한 inode들의 수에 대한 통계 출력:

```bash
df -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | df: add more information link (#5557) | 2021-03-30T12:23:41 | [0812ddae5287](https://github.com/tldr-pages/tldr/commit/0812ddae5287591cb1f8064bf5eb63033cadf39b)
[Proscream](mailto:proscream@naver.com) | df: Add Korean Translation (#3676) | 2019-12-26T14:42:48 | [ce92e307e9ea](https://github.com/tldr-pages/tldr/commit/ce92e307e9eaff7f4b730be5c7c97256324dea52)

