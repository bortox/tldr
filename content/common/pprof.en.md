---
author: ['Antoine Amara']
date: 1574793522
title: "pprof, TLDR Pages"
description: "pprof, Command-line tool for visualization and analysis of profile data."
categories: "common"
---
> More information: <https://github.com/google/pprof>.

- Generate a text report from a specific profiling file, on fibbo binary:

```bash
pprof -top ./fibbo ./fibbo-profile.pb.gz
```

- Generate a graph and open it on a web browser:

```bash
pprof -svg ./fibbo ./fibbo-profile.pb.gz
```

- Run pprof in interactive mode to be able to manually launch `pprof` on a file:

```bash
pprof ./fibbo ./fibbo-profile.pb.gz
```

- Run a web server that serves a web interface on top of `pprof`:

```bash
pprof -http=localhost:8080 ./fibbo ./fibbo-profile.pb.gz
```

- Fetch a profile from an HTTP server and generate a report:

```bash
pprof http://localhost:8080/debug/pprof
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Amara](mailto:amara.antoine@gmail.com) | pprof: add new page (#3450) | 2019-11-26T19:38:42 | [a63157edc1c4](https://github.com/tldr-pages/tldr/commit/a63157edc1c4b91138693b392b58bc738de8d3a9)

