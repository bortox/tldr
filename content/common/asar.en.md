---
author: ['Schneider', 'Jan T. Sott', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "asar"
description: "asar, A file archiver for the Electron platform."
categories: "common"
---
> More information: <https://github.com/electron/asar>.

- Archive a file or directory:

```bash
asar pack path/to/file_or_directory archived.asar
```

- Extract an archive:

```bash
asar extract archived.asar
```

- Extract a specific file from an archive:

```bash
asar extract-file archived.asar file
```

- List the contents of an archive file:

```bash
asar list archived.asar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | asar.md: add homepage | 2019-04-12T14:41:22 | [5e3d4a6028f8](https://github.com/tldr-pages/tldr/commit/5e3d4a6028f839d67cbac09dc16993c09e975c53)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | asar: make consistent with 7z description (#2325) | 2018-09-12T11:28:40 | [b3b9e387c463](https://github.com/tldr-pages/tldr/commit/b3b9e387c4631fbd012e90651eed4802cd74cad7)
[Jan T. Sott](mailto:jan@idleberg.com) | asar: add page (#2317) | 2018-09-09T16:15:25 | [929be662beed](https://github.com/tldr-pages/tldr/commit/929be662beedb10c9189689a7910b5520a6c718a)

