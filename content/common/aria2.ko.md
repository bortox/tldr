---
author: ['Marco Bonelli', 'Seth Falco', 'Proscream']
date: 1648358715
title: "aria2, TLDR Pages"
description: "aria2, 경량 멀티 프로토콜 및 멀티 소스 명령줄 다운로드 유틸리티입니다."
categories: "common"
---
> HTTP, HTTPS, FTP, SFTP, BitTorrent와 Metalink를 지원합니다.

> 더 많은 정보: <https://aria2.github.io/>.

- 웹 리소스 다운로드:

```bash
aria2c http://example.org/myLinux.iso
```

- 멀티 소스 리소스 다운로드:

```bash
aria2c http://mirror1.org/myLinux.iso http://mirror2.org/myLinux.iso
```

- 호스트당 2개의 연결을 사용하여 다운로드:

```bash
aria2c -x2 http://example.org/myLinux.iso
```

- Metalink URL로 다운로드:

```bash
aria2c http://example.org/myLinux.metalink
```

- BitTorrent URI로 다운로드:

```bash
aria2c http://example.org/myLinux.torrent
```

- BitTorrent Magnet URI로 다운로드:

```bash
aria2c 'magnet:?xt=urn:btih:248D0A1CD08284299DE78D5C1ED359BB46717D8C'
```

- 파일로 URls 다운로드:

```bash
aria2c -i uris.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3560) | 2019-11-14T02:44:51 | [4f797eb4ef82](https://github.com/tldr-pages/tldr/commit/4f797eb4ef827d22f1001a95c5eca8f03aebddc8)

