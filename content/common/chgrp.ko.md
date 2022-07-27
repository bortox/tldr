---
author: ['Dario Vladović', 'marchersimon', 'Proscream']
date: 1617292466
title: "chgrp, TLDR Pages"
description: "chgrp, 파일 및 디렉토리의 그룹 소유권 변경."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/chgrp>.

- 파일/디렉토리의 소유 그룹 변경:

```bash
chgrp 그룹 경로/파일명_또는_디렉토리명
```

- 디렉토리 및 해당 컨텐츠의 소유 그룹 변경:

```bash
chgrp -R 그룹 경로/디렉토리명
```

- 심볼릭 링크의 소유 그룹 변경:

```bash
chgrp -h 그룹 경로/심볼릭_링크
```

- 참조 파일과 일치하도록 파일/디렉토리의 소유 그룹 변경:

```bash
chgrp --reference=경로/참조_파일명 경로/파일명_또는_디렉토리명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chgrp: add more information link (#5554) | 2021-03-30T12:33:21 | [1bee28dd6572](https://github.com/tldr-pages/tldr/commit/1bee28dd6572c855d7cdb2ffd88e05794a8cfc86)
[Proscream](mailto:proscream@naver.com) | Multiple Pages(cat to chgrp) : Add Korean Translation (#3585) | 2019-11-19T18:12:39 | [f07d3ea376c1](https://github.com/tldr-pages/tldr/commit/f07d3ea376c17a5b3483e8aad4f5f370eda64d0a)

