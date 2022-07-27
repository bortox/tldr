---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'Starbeamrainbowlabs']
date: 1612112718
title: "git format-patch, TLDR Pages"
description: "git format-patch, Prepare .patch files. Useful when emailing commits elsewhere."
categories: "common"
---
> See also `git am`, which can apply generated .patch files.

> More information: <https://git-scm.com/docs/git-format-patch>.

- Create an auto-named `.patch` file for all the unpushed commits:

```bash
git format-patch origin
```

- Write a `.patch` file for all the commits between 2 revisions to stdout:

```bash
git format-patch revision_1..revision_2
```

- Write a `.patch` file for the 3 latest commits:

```bash
git format-patch -3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git format patch: add page (#2351) | 2018-09-25T20:40:23 | [28adcbcebdeb](https://github.com/tldr-pages/tldr/commit/28adcbcebdebb933a34deac0fe7994ddf5130b99)

