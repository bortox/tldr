---
author: ['hellojukay']
date: 1648999508
title: "you-get, TLDR Pages"
description: "you-get, Download media contents (videos, audios, images) from the Web."
categories: "common"
---
> More information: <https://you-get.org>.

- Print media information about a specific media on the web:

```bash
you-get --info https://example.com/video?id=value
```

- Download a media from a specific URL:

```bash
you-get https://example.com/video?id=value
```

- Search on Google Videos and download:

```bash
you-get keywords
```

- Download a media to a specific location:

```bash
you-get --output-dir path/to/directory --output-filename filename https://example.com/watch?v=value
```

- Download a media using a proxy:

```bash
you-get --http-proxy proxy_server https://example.com/watch?v=value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[hellojukay](mailto:hellojukay@163.com) | you-get: add page (#7948) | 2022-04-03T17:25:08 | [2bf7c9a67007](https://github.com/tldr-pages/tldr/commit/2bf7c9a670074e3ddd05d66d78f07a5a67482c5c)

