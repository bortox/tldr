---
author: ['Starbeamrainbowlabs', 'lucas schneider', 'Seth Falco']
date: 1629050349
title: "git instaweb"
description: "git instaweb, Helper to launch a GitWeb server."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-instaweb>.

- Launch a GitWeb server for the current Git repository:

```bash
git instaweb --start
```

- Listen only on localhost:

```bash
git instaweb --start --local
```

- Listen on a specific port:

```bash
git instaweb --start --port 1234
```

- Use a specified HTTP daemon:

```bash
git instaweb --start --httpd lighttpd|apache2|mongoose|plackup|webrick
```

- Also auto-launch a web browser:

```bash
git instaweb --start --browser
```

- Stop the currently running GitWeb server:

```bash
git instaweb --stop
```

- Restart the currently running GitWeb server:

```bash
git instaweb --restart
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[lucas schneider](mailto:casdpa@gmail.com) | add missing pages | 2021-01-08T14:09:54 | [8d60f149451e](https://github.com/tldr-pages/tldr/commit/8d60f149451ebfc54332af0c2678732cc324d4e4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-instaweb: add page (#4017) | 2020-05-10T14:41:53 | [ac75e5f12c3d](https://github.com/tldr-pages/tldr/commit/ac75e5f12c3d91f9d7fb557629e7ed967e564cc3)

