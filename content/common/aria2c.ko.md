---
author: ['Proscream', 'Seth Falco', 'Marco Bonelli']
date: 1648358715
title: "aria2c"
description: "aria2c, 빠른 다운로드 유틸리티."
categories: "common"
---
> HTTP(S), FTP, SFTP, BitTorrent, and Metalink를 지원합니다.

> 더 많은 정보: <https://aria2.github.io>.

- URl을 파일에 다운로드:

```bash
aria2c url
```

- 다중 소스를 다운로드:

```bash
aria2c url_1 url_2
```

- 파일에 나열된 URI 다운로드:

```bash
aria2c -i filename
```

- 여러 연결로 다운로드:

```bash
aria2c -s connections_num url
```

- 사용자 이름과 암호가 있는 FTP 다운로드:

```bash
aria2c --ftp-user=username --ftp-passwd=password url
```

- 다운로드 속도를 바이트/s로 제한:

```bash
aria2c --max-download-limit=speed url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add missing trailing newline to some Korean pages. (#3575) | 2019-11-15T18:01:53 | [7f699a83abd0](https://github.com/tldr-pages/tldr/commit/7f699a83abd08868a78220fb3222aa455974fd2a)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3560) | 2019-11-14T02:44:51 | [4f797eb4ef82](https://github.com/tldr-pages/tldr/commit/4f797eb4ef827d22f1001a95c5eca8f03aebddc8)

