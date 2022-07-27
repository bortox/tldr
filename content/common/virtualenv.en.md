---
author: ["echo $USER - sed 's/cp/c p/", 'Son Pham', 'Marco Bonelli', 'Ruben Vereecken', 'zlbabe', 'Balázs Úr', 'Starbeamrainbowlabs']
date: 1559564381
title: "virtualenv, TLDR Pages"
description: "virtualenv, Create virtual isolated Python environments."
categories: "common"
---
> More information: <https://virtualenv.pypa.io/>.

- Create a new environment:

```bash
virtualenv path/to/venv
```

- Customize the prompt prefix:

```bash
virtualenv --prompt=prompt_prefix path/to/venv
```

- Use a different version of Python with virtualenv:

```bash
virtualenv --python=path/to/pythonbin path/to/venv
```

- Start (select) the environment:

```bash
source path/to/venv/bin/activate
```

- Stop the environment:

```bash
deactivate
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[echo $USER - sed 's/cp/c p/](mailto:2423679+ericpardee@users.noreply.github.com) | virtualenv: add python version example (#2851) | 2019-03-27T00:41:33 | [209ceee8765c](https://github.com/tldr-pages/tldr/commit/209ceee8765c4dec78f0b20c1dc88d794b6ba4f3)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | virtualenv: add --prompt option (#2356) | 2018-09-29T08:14:42 | [9b647a7c0f3b](https://github.com/tldr-pages/tldr/commit/9b647a7c0f3b77088dcb5521dce961d7dc3e5827)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Son Pham](mailto:sonpa1993@gmail.com) | add virtualenv page | 2015-12-30T21:01:43 | [9f3b9aa636d3](https://github.com/tldr-pages/tldr/commit/9f3b9aa636d353d8f6eac64cc3a0a7c988175863)

