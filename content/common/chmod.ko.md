---
author: ['Dario Vladović', 'Proscream', 'marchersimon']
date: 1617292466
title: "chmod"
description: "chmod, 파일이나 디렉토리의 연결 권한 변경."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/chmod>.

- 파일을 소유한 사용자[u]에게 실행[x] 권한 부여:

```bash
chmod u+x 파일명
```

- 파일/디렉토리에 읽기[r] 와 쓰기[w] 사용자 권한 부여:

```bash
chmod u+rw 파일명_또는_디렉토리명
```

- 그룹[g]에서 실행 권한 제거:

```bash
chmod g-x 파일명
```

- 모든[a] 사용자에게 읽기 및 실행 권한 부여:

```bash
chmod a+rx 파일명
```

- 다른[o] 사람(파일 소유자의 그룹이 아님)에게 그룹과 동일한 권한 부여:

```bash
chmod o=g 파일명
```

- 그룹[g] 및 다른 사람[o]에 대한 쓰기[w]에 대한 권한을 재귀적으로 변경:

```bash
chmod -R g+w,o+w 디렉토리명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[Proscream](mailto:proscream@naver.com) | Multiple pages(chisel to chroot) : Add Korean Translation (#3586) | 2019-11-19T18:22:39 | [bfbe15c8e437](https://github.com/tldr-pages/tldr/commit/bfbe15c8e4378a26e43b9dfe6f4ce65e2222df02)

