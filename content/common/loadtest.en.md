---
author: ['Thamaraiselvam']
date: 1633856960
title: "loadtest, TLDR Pages"
description: "loadtest, Run a load test on the selected HTTP or WebSockets URL."
categories: "common"
---
> More information: <https://github.com/alexfernandez/loadtest>.

- Run with concurrent users and a specified amount of requests per second:

```bash
loadtest --concurrency 10 --rps 200 https://example.com
```

- Run with a custom HTTP header:

```bash
loadtest --headers "accept:text/plain;text-html" https://example.com
```

- Run with a specific HTTP method:

```bash
loadtest --method GET https://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Thamaraiselvam](mailto:thamaraiselvam@live.com) | loadtest: add page (#6923) | 2021-10-10T11:09:20 | [43c9164d69dc](https://github.com/tldr-pages/tldr/commit/43c9164d69dc22158f9a100d6f762d18ab8359ea)

