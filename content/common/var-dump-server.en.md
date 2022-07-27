---
author: ['Pierre Rudloff']
date: 1601670520
title: "var-dump-server, TLDR Pages"
description: "var-dump-server, Symfony dump server."
categories: "common"
---
> Collects data dumped by the Symfony VarDumper component.

> More information: <https://symfony.com/doc/current/components/var_dumper.html#the-dump-server>.

- Start the server:

```bash
var-dump-server
```

- Dump the data in an HTML file:

```bash
var-dump-server --format=html > path/to/file.html
```

- Make the server listen on a specific address and port:

```bash
var-dump-server --host 127.0.0.1:9912
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | var-dump-server: add page (#4408) | 2020-10-02T22:28:40 | [812687f9bc7e](https://github.com/tldr-pages/tldr/commit/812687f9bc7eee66665abae039ca3990015e1c43)

