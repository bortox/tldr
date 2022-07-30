---
author: ['Peter Tripp', 'Seth Falco', 'BillLucky']
date: 1629050349
title: "jhat"
description: "jhat, Java Heap Analysis Tool."
categories: "common"
---
> More information: <https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html>.

- Analyze a heap dump (from `jmap`), view via HTTP on port 7000:

```bash
jhat dump_file.bin
```

- Analyze a heap dump, specifying an alternate port for the http server:

```bash
jhat -p port dump_file.bin
```

- Analyze a dump letting `jhat` use up to 8 GB RAM (2-4x dump size recommended):

```bash
jhat -J-mx8G dump_file.bin
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[BillLucky](mailto:bill.libiao@gmail.com) | jhat: add more information link (#6266) | 2021-07-26T18:52:14 | [184234db8580](https://github.com/tldr-pages/tldr/commit/184234db85806e83b638519d77c9594919c92caf)
[Peter Tripp](mailto:peter@chartio.com) | Add jhat example with larger memory limit. | 2016-02-17T01:32:26 | [f8d9ee3a3508](https://github.com/tldr-pages/tldr/commit/f8d9ee3a3508845bfc4f8b2a58941ea5cf2f8f89)
[Peter Tripp](mailto:peter@chartio.com) | Java debug tools. Jstack, jmap and jhat. | 2016-02-16T20:27:52 | [67e2c723aff4](https://github.com/tldr-pages/tldr/commit/67e2c723aff4502501e0ac567ac5364348f6f3d7)

