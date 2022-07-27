---
author: ['Sakthivel Balasubramaniam']
date: 1571255890
title: "pageres, TLDR Pages"
description: "pageres, Capture screenshots of websites in various resolutions."
categories: "common"
---
> More information: <https://github.com/sindresorhus/pageres-cli>.

- Take multiple screenshots of multiple URLs at different resolutions:

```bash
pageres https://example.com/ https://example2.com/ 1366x768 1600x900
```

- Provide specific options for a URL, overriding global options:

```bash
pageres [https://example.com/ 1366x768 --no-crop] [https://example2.com/ 1024x768] --crop
```

- Provide a custom filename template:

```bash
pageres https://example.com/ 1024x768 --filename='<%= date %> - <%= url %>'
```

- Capture a specific element on a page:

```bash
pageres https://example.com/ 1366x768 --selector='.page-header'
```

- Hide a specific element:

```bash
pageres https://example.com/ 1366x768 --hide='.page-header'
```

- Capture a screenshot of a local file:

```bash
pageres local_file_path.html 1366x768
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sakthivel Balasubramaniam](mailto:8691700+ImShakthi@users.noreply.github.com) | pageres: add page (#3377) | 2019-10-16T21:58:10 | [8f5d68b7d086](https://github.com/tldr-pages/tldr/commit/8f5d68b7d086eaed5cb1d22fecf4b95768888b1a)

