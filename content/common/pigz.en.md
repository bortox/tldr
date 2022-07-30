---
author: ['mtonsmann', 'pxgamer', 'cPlevey', 'Ruben Vereecken']
date: 1561596287
title: "pigz"
description: "pigz, Multithreaded zlib compression utility."
categories: "common"
---
> More information: <https://github.com/madler/pigz>.

- Compress a file with default options:

```bash
pigz filename
```

- Compress a file using the best compression method:

```bash
pigz -9 filename
```

- Compress a file using no compression and 4 processors:

```bash
pigz -0 -p4 filename
```

- Compress a directory using tar:

```bash
tar cf - path/to/directory | pigz > filename.tar.gz
```

- Decompress a file:

```bash
pigz -d archive.gz
```

- List the contents of an archive:

```bash
pigz -l archive.tar.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[mtonsmann](mailto:marcus@tonsmann.net) | pigz: add directory compression example (#3139) | 2019-06-27T02:44:47 | [613e1713186c](https://github.com/tldr-pages/tldr/commit/613e1713186c9864fa1222c0cdc67dd668cff493)
[pxgamer](mailto:owzie123@gmail.com) | pigz: add link to homepage | 2019-05-31T20:47:40 | [3a8d7be9daf5](https://github.com/tldr-pages/tldr/commit/3a8d7be9daf51d093281afb866c5f4a23218ae3c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Edited pigz to more fitting examples | 2016-01-25T00:24:49 | [a5409ed43784](https://github.com/tldr-pages/tldr/commit/a5409ed43784ba0dcbe6dc519dfc432b3a6a4209)
[cPlevey](mailto:cplevey@gmail.com) | added pigz | 2016-01-14T13:12:09 | [e30345bfde6c](https://github.com/tldr-pages/tldr/commit/e30345bfde6c49171ea18d45f5ec93114b45d3b2)

