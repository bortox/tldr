---
author: ['Pierre Rudloff']
date: 1574024154
title: "rtmpdump"
description: "rtmpdump, A tool to dump media content streamed over the RTMP protocol."
categories: "common"
---
> More information: <http://rtmpdump.mplayerhq.hu/>.

- Download a file:

```bash
rtmpdump --rtmp rtmp://example.com/path/to/video -o file.ext
```

- Download a file from a Flash player:

```bash
rtmpdump --rtmp rtmp://example.com/path/to/video --swfVfy http://example.com/player --flashVer "LNX 10,0,32,18" -o file.ext
```

- Specify connection parameters if they are not detected correctly:

```bash
rtmpdump --rtmp rtmp://example.com/path/to/video --app app_name --playpath path/to/video -o file.ext
```

- Download a file from a server that requires a referrer:

```bash
rtmpdump --rtmp rtmp://example.com/path/to/video --pageUrl http://example.com/webpage -o file.ext
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | rtmpdump: add page (#3551) | 2019-11-17T21:55:54 | [eedfae7af831](https://github.com/tldr-pages/tldr/commit/eedfae7af8312b372ccf72381f4c66805ebf7fbc)

