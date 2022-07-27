---
author: ['Patrice Denis', 'bl-ue']
date: 1618661981
title: "deluser, TLDR Pages"
description: "deluser, 유저 계정 제거 또는 그룹으로부터 사용자 제거."
categories: "linux"
---
> 더 많은 정보: <https://manpages.debian.org/latest/adduser/deluser.html>.

- 유저 삭제:

```bash
deluser 이름
```

- 사용자의 홈 디렉토리 및 메일 스풀과 함께 사용자 제거:

```bash
deluser -r 이름
```

- 그룹으로부터 사용자 제거:

```bash
deluser 이름 그룹
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | deluser: sync translations with PR #5245 (#5355) | 2021-03-08T20:49:49 | [c81f9c7b1799](https://github.com/tldr-pages/tldr/commit/c81f9c7b1799a7ff1bc909f372d1f87ec8290365)

