---
author: ['Dario Vladović', 'bl-ue', 'Proscream', 'marchersimon']
date: 1617493464
title: "dirname"
description: "dirname, 주어진 파일 혹은 디렉토리 경로의 부모 디렉토리를 계산한다."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/dirname>.

- 주어진 경로의 부모 디렉토리 계산:

```bash
dirname 경로/파일_또는_디렉토리
```

- 복수 경로의 부모 디렉토리 계산:

```bash
dirname 경로/a_파일 경로/b_디렉토리
```

- 개행 대신 NUL 문자로 출력을 구분하기 (`xargs`와 결합 시 유용함):

```bash
dirname --zero 경로/a_디렉토리 경로/b_파일
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirname: add link (#5604) | 2021-03-30T15:55:16 | [016c255e46ff](https://github.com/tldr-pages/tldr/commit/016c255e46ff9a07e2a8bf279a039cb6cfddfdb8)
[Proscream](mailto:proscream@naver.com) | dirname: Add Korean Translation (#3741) | 2020-01-09T04:05:07 | [36ac3c5e8d93](https://github.com/tldr-pages/tldr/commit/36ac3c5e8d931093fd0794fa7868819a966c7848)

