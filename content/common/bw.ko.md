---
author: ['Proscream']
date: 1574024304
title: "bw, TLDR Pages"
description: "bw, Bitwarden 보관함에 접속과 관리를 위한 CLI."
categories: "common"
---
> 더 많은 정보: <https://help.bitwarden.com/article/cli/>.

- Bitwarden 사용자 계정 로그인:

```bash
bw login
```

- 사용자 계정 로그아웃:

```bash
bw logout
```

- Bitwarden 보관함으로부터 아이템 검색과 출력:

```bash
bw list items --search github
```

- Bitwarden 보관함으로부터 특정 아이템 출력:

```bash
bw get item github
```

- Bitwarden 보관함에 폴더 생성:

```bash
echo -n '{"name":"My Folder1"}' | base64 | bw create folder
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Proscream](mailto:proscream@naver.com) | bw : Add Korean Translation (#3578) | 2019-11-17T21:58:24 | [142e70accd0f](https://github.com/tldr-pages/tldr/commit/142e70accd0fa2ce3243e2281a69273c47bfb52e)

