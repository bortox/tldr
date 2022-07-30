---
author: ['Florian', 'bl-ue', 'Lucas Gabriel Schneider']
date: 1612112718
title: "lzop"
description: "lzop, Compress or decompress files with LZO compression."
categories: "common"
---
> More information: <https://www.lzop.org/>.

- Compress a file into a new file with the `.lzo` suffix:

```bash
lzop file
```

- Decompress a file:

```bash
lzop -d file.lzo
```

- Compress a file, while specifying the compression level. 0 = Worst, 9 = Best (Default level is 3):

```bash
lzop -level file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Florian](mailto:KopfKrieg@users.noreply.github.com) | lzop: add page (#3791) | 2020-01-28T20:12:51 | [f1e65d27c04f](https://github.com/tldr-pages/tldr/commit/f1e65d27c04f721655841df7015ee94e396d6188)

