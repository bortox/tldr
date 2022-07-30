---
author: ['Dario Vladović', 'Schneider', 'Lucas Gabriel Schneider', 'JJByun', 'marchersimon']
date: 1617292466
title: "comm"
description: "comm, 두 파일의 공통되는 줄을 선택하거나 거절합니다."
categories: "common"
---
> 두 파일 모두 정렬되어 있어야합니다.

> 더 많은 정보: <https://www.gnu.org/software/coreutils/comm>.

- 세 개의 탭으로 구분된 열을 생성합니다: 첫 번째 파일에는 줄만, 두 번째 파일에서는 줄들과 공통 줄:

```bash
comm 파일1 파일2
```

- 두 파일의 공통된 줄들만 출력:

```bash
comm -12 파일1 파일2
```

- stdin으로 읽어드린 하나의 파일과 나머지 파일의 공통된 줄들만 출력:

```bash
cat 파일1 | comm -12 - 파일2
```

- 첫 번째 파일에서만 줄을 가져오고 결과를 세 번째 파일에 저장:

```bash
comm -23 파일1 파일2 > 파일1_only
```

- 파일이 정렬되지 않은 경우 두 번째 파일에서만 줄을 출력합니다:

```bash
comm -13 <(sort 파일1) <(sort 파일2)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | comm: add link (#5574) | 2021-03-30T13:45:00 | [d2f1b60f45aa](https://github.com/tldr-pages/tldr/commit/d2f1b60f45aa596ac50271f9f18ad69817e3eb26)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[JJByun](mailto:jd0909@naver.com) | merge mutiple pages(cmake to command) : Add Korean Translation (#3595) * korean translation cmake cmark cmp code coffee column comm [...] | 2019-11-22T16:25:18 | [61f5b847208b](https://github.com/tldr-pages/tldr/commit/61f5b847208bf1994b04849aaa5d16948f1716b5)

