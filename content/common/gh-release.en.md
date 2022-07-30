---
author: ['bl-ue', 'Abel']
date: 1621541621
title: "gh release"
description: "gh release, Manage GitHub releases from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_release>.

- List releases in a GitHub repository, limited to 30 items:

```bash
gh release list
```

- Display information about a specific release:

```bash
gh release view tag
```

- Create a new release:

```bash
gh release create tag
```

- Delete a specific release:

```bash
gh release delete tag
```

- Download assets from a specific release:

```bash
gh release download tag
```

- Upload assets to a specific release:

```bash
gh release upload tag path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Abel](mailto:abel.tay@gmail.com) | gh-release: add page (#4773) | 2020-10-24T15:09:49 | [a773331d60b0](https://github.com/tldr-pages/tldr/commit/a773331d60b0dba9844b3709e51be6d8743dd5df)

