---
author: ['Dario Vladović', 'marchersimon', 'Proscream']
date: 1617292466
title: "cat, TLDR Pages"
description: "cat, 파일 출력 및 연결."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/cat>.

- 표준출력으로 파일 내용 출력:

```bash
cat 파일명
```

- 여러 파일을 대상 파일에 연결:

```bash
cat 파일명1 파일명2 > 대상_파일명
```

- 대상 파일에 여러 파일 내용 추가:

```bash
cat 파일명1 파일명2 >> 대상_파일명
```

- 모든 출력 라인에 번호 매기기:

```bash
cat -n 파일명
```

- 출력할 수 없는 문자 및 공백 문자 표시 (ASCII가 아닌 경우 `M-`접두사 포함):

```bash
cat -v -t -e 파일명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Proscream](mailto:proscream@naver.com) | Multiple Pages(cat to chgrp) : Add Korean Translation (#3585) | 2019-11-19T18:12:39 | [f07d3ea376c1](https://github.com/tldr-pages/tldr/commit/f07d3ea376c17a5b3483e8aad4f5f370eda64d0a)

