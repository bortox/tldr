---
author: ['Waldir Pimenta', 'Owen Voke', 'Honza', 'Marco Bonelli', 'Ran Yitzhaki', 'marchersimon']
date: 1620637392
title: "z"
description: "z, Tracks the most used (by frecency) directories and enables quickly navigating to them using string patterns or regular expressions."
categories: "common"
---
> More information: <https://github.com/rupa/z>.

- Go to a directory that contains "foo" in the name:

```bash
z foo
```

- Go to a directory that contains "foo" and then "bar":

```bash
z foo bar
```

- Go to the highest-ranked directory matching "foo":

```bash
z -r foo
```

- Go to the most recently accessed directory matching "foo":

```bash
z -t foo
```

- List all directories in `z`'s database matching "foo":

```bash
z -l foo
```

- Remove the current directory from `z`'s database:

```bash
z -x .
```

- Restrict matches to subdirectories of the current directory:

```bash
z -c foo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Honza](mailto:info@planxdesign.eu) | z: add `-c` parameter to the command description (#5262) | 2021-02-19T00:13:08 | [49852ef289a0](https://github.com/tldr-pages/tldr/commit/49852ef289a0a397eff71178977e46e7c437ce3e)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | z: reword descriptions for clarity | 2017-09-14T06:28:50 | [66e189d2211b](https://github.com/tldr-pages/tldr/commit/66e189d2211b0d16930fce5cd578fd124327b1f8)
[Ran Yitzhaki](mailto:ranyitz@users.noreply.github.com) | z.md: add page (#1442) | 2017-08-10T19:50:04 | [3cc612800e98](https://github.com/tldr-pages/tldr/commit/3cc612800e98ec0b6614c87bf35824ab1178eef5)

