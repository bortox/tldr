---
author: ['marchersimon', 'Proscream']
date: 1618869951
title: "dirs, TLDR Pages"
description: "dirs, 디렉토리 스택을 표시하거나 조작한다."
categories: "common"
---
> 디렉토리 스택은 `pushd`과 `popd` 명령어로 조작할 수 있는 최근 방문한 디렉토리의 목록이다.

> 더 많은 정보: <https://www.gnu.org/software/bash/manual/bash.html#Directory-Stack-Builtins>.

- 각각의 엔트리 사이에서 공백으로 디렉토리 스택을 표시하기:

```bash
dirs
```

- 하나의 엔트리에 하나의 라인으로 디렉토리 스택 표시하기:

```bash
dirs -p
```

- 0부터 시작하는 디렉토리 스택에 n번째 항만 표시하기:

```bash
dirs +N
```

- 디렉토리 스택 초기화하기:

```bash
dirs -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirs: edit link Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-20T00:05:51 | [5d2fa2261db4](https://github.com/tldr-pages/tldr/commit/5d2fa2261db4d26e09c26f72f35d52e35dcf1bec)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Proscream](mailto:proscream@naver.com) | dirs: Add Korean Translation (#3745) | 2020-01-09T20:08:22 | [39eb7831dda3](https://github.com/tldr-pages/tldr/commit/39eb7831dda3448084fa26a753fca67f5d896f90)

