---
author: ['dmakth']
date: 1574410217
title: "darkhttpd"
description: "darkhttpd, Darkhttpd 웹 서버."
categories: "common"
---
> 더 많은 정보: <https://unix4lyfe.org/darkhttpd>.

- 지정된 문서 경로를 제공하는 서버 시작:

```bash
darkhttpd 경로/문서
```

- 지정된 포트에서 서버 시작(루트가 아닌 사용자로 시작되는 경우 8080포트가 기본값):

```bash
darkhttpd 경로/문서 --port 포트번호
```

- 지정된 IP 주소에서만 수신 (기본적으로 서버는 모든 인터페이스에서 수신):

```bash
darkhttpd 경로/문서 --addr ip주소
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

