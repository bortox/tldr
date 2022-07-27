---
author: ['Marco Bonelli', 'Agniva De Sarker', 'Owen Voke']
date: 1559564381
title: "wat2wasm, TLDR Pages"
description: "wat2wasm, Convert a file from the WebAssembly text format to the binary format."
categories: "common"
---
> More information: <https://github.com/WebAssembly/wabt>.

- Parse and check a file for errors:

```bash
wat2wasm file.wat
```

- Write the output binary to a given file:

```bash
wat2wasm file.wat -o file.wasm
```

- Display simplified representation of every byte:

```bash
wat2wasm -v file.wat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | wat2wasm: add page (#2359) | 2018-10-01T18:18:32 | [747dd0f79961](https://github.com/tldr-pages/tldr/commit/747dd0f79961e904adbfab5f2372cb99f46fd7eb)

