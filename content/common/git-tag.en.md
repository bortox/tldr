---
author: ['Waldir Pimenta', 'Igor Shubovych', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Jibran Kalia', 'Ruben Vereecken']
date: 1559564381
title: "git tag"
description: "git tag, Create, list, delete or verify tags."
categories: "common"
---
> A tag is a static reference to a specific commit.

> More information: <https://git-scm.com/docs/git-tag>.

- List all tags:

```bash
git tag
```

- Create a tag with the given name pointing to the current commit:

```bash
git tag tag_name
```

- Create a tag with the given name pointing to a given commit:

```bash
git tag tag_name commit
```

- Create an annotated tag with the given message:

```bash
git tag tag_name -m tag_message
```

- Delete the tag with the given name:

```bash
git tag -d tag_name
```

- Get updated tags from upstream:

```bash
git fetch --tags
```

- List all tags whose ancestors include a given commit:

```bash
git tag --contains commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Jibran Kalia](mailto:jibran.kalia@gmail.com) | git-tag: Add message for given commit (#1877) | 2018-01-10T11:52:20 | [0a5a62eda8de](https://github.com/tldr-pages/tldr/commit/0a5a62eda8de92a213b26ddc1411a3e392f50303)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | make desc more explicit | 2017-01-10T06:17:29 | [c5eb598d5c0e](https://github.com/tldr-pages/tldr/commit/c5eb598d5c0ed0562edb32a4ec13afc4ad77047a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix --contains example | 2017-01-10T06:17:29 | [e6b9f81cd6ed](https://github.com/tldr-pages/tldr/commit/e6b9f81cd6ed759262800339d66b130c4e1f53ac)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-tag: add --contains example | 2017-01-10T06:17:29 | [e50923393346](https://github.com/tldr-pages/tldr/commit/e50923393346f0d03d4ee8d15ee46665373f3adb)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-tag, git-fetch: add example for fetching tags (#1128) | 2016-10-27T06:55:22 | [173d3533755c](https://github.com/tldr-pages/tldr/commit/173d3533755c1f19f4bb2903eb1d047199d2d623)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | git-tag: Clarified how to create annotation | 2016-01-13T12:33:17 | [10ead941f7b1](https://github.com/tldr-pages/tldr/commit/10ead941f7b1cbb715f09955aab5f134e1f0424f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | git-tag: add page; git-push: add example of pushing tags | 2015-12-19T23:31:52 | [3e3f3e411e88](https://github.com/tldr-pages/tldr/commit/3e3f3e411e88a1cbdf1008db75ee0c828c86403d)

