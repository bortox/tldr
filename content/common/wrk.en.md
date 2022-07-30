---
author: ['HARSHIT GUPTA', 'Ivan Aracki', 'Marco Bonelli']
date: 1580398615
title: "wrk"
description: "wrk, HTTP benchmarking tool."
categories: "common"
---
> More information: <https://github.com/wg/wrk>.

- Run a benchmark for `30` seconds, using `12` threads, and keeping `400` HTTP connections open:

```bash
wrk -t12 -c400 -d30s "http://127.0.0.1:8080/index.html"
```

- Run a benchmark with a custom header:

```bash
wrk -t2 -c5 -d5s -H "Host: example.com" "http://example.com/index.html"
```

- Run a benchmark with a request timeout of `2` seconds:

```bash
wrk -t2 -c5 -d5s --timeout 2s "http://example.com/index.html"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[HARSHIT GUPTA](mailto:harshitsaamu@gmail.com) | wrk: fix typo (#3822) * wrk: fix typo * Update pages/common/wrk.md Co-Authored-By: Owen Voke <owzie123@gmail.com> Co-authored-by: Owen [...] | 2020-01-30T16:36:55 | [80ab4215db4d](https://github.com/tldr-pages/tldr/commit/80ab4215db4dc375a3b5c1336227b5d8904f1ddf)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | wrk: add page (#2971) | 2019-05-10T20:22:41 | [d0d2eeced2fc](https://github.com/tldr-pages/tldr/commit/d0d2eeced2fc47a23a5bd7b482b06021e8fd3feb)

