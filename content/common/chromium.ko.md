---
author: ['Marco Bonelli', 'Proscream', 'marchersimon']
date: 1659075216
title: "chromium"
description: "chromium, 구글에서 제공하는 오픈소스 웹 브라우저."
categories: "common"
---
> 더 많은 정보: <https://www.chromium.org/developers/how-tos/run-chromium-with-flags/>.

- 파일 열기:

```bash
chromium 경로/파일명.html
```

- URL 열기:

```bash
chromium example.com
```

- 익명으로 열기:

```bash
chromium --incognito example.com
```

- 새 창에서 열기:

```bash
chromium --new-window example.com
```

- 앱 모드로 열기 (툴바, URL 바, 버튼 등 제외):

```bash
chromium --app='https://example.com'
```

- 프록시 서버 사용:

```bash
chromium --proxy-server="socks5://hostname:66" example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | Multiple pages(chisel to chroot) : Add Korean Translation (#3586) | 2019-11-19T18:22:39 | [bfbe15c8e437](https://github.com/tldr-pages/tldr/commit/bfbe15c8e4378a26e43b9dfe6f4ce65e2222df02)

