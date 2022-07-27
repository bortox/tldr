---
author: ['Schneider', 'Owen Voke', 'Marco Bonelli', 'Jonathan Dahan', 'bl-ue']
date: 1621541621
title: "xsv, TLDR Pages"
description: "xsv, A CSV command-line toolkit written in Rust."
categories: "common"
---
> More information: <https://github.com/BurntSushi/xsv>.

- Inspect the headers of a file:

```bash
xsv headers path/to/file.csv
```

- Count the number of entries:

```bash
xsv count path/to/file.csv
```

- Get an overview of the shape of entries:

```bash
xsv stats path/to/file.csv | xsv table
```

- Select a few columns:

```bash
xsv select column_a,column_b path/to/file.csv
```

- Show 10 random entries:

```bash
xsv sample 10 path/to/file.csv
```

- Join a column from one file to another:

```bash
xsv join --no-case column_a path/to/file/a.csv column_b path/to/file/b.csv | xsv table
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Jonathan Dahan](mailto:hi@jonathan.is) | xsv: add page (#2366) | 2018-10-22T22:51:33 | [2d5b94c00ace](https://github.com/tldr-pages/tldr/commit/2d5b94c00ace183ebc13183e85d7acf189f95c68)

