---
author: ['Henning Pohlmeyer', 'kalebo', 'André König', 'Eric Nielsen', 'rprieto', 'Marco Bonelli', 'Starbeamrainbowlabs', 'Frank', 'Ruben Vereecken']
date: 1559641216
title: "git stash"
description: "git stash, Stash local Git changes in a temporary area."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-stash>.

- Stash current changes, except new (untracked) files:

```bash
git stash [push -m optional_stash_message]
```

- Stash current changes, including new (untracked) files:

```bash
git stash -u
```

- Interactively select parts of changed files for stashing:

```bash
git stash -p
```

- List all stashes (shows stash name, related branch and message):

```bash
git stash list
```

- Apply a stash (default is the latest, named stash@{0}):

```bash
git stash apply optional_stash_name_or_commit
```

- Apply a stash (default is stash@{0}), and remove it from the stash list if applying doesn't cause conflicts:

```bash
git stash pop optional_stash_name
```

- Drop a stash (default is stash@{0}):

```bash
git stash drop optional_stash_name
```

- Drop all stashes:

```bash
git stash clear
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henning Pohlmeyer](mailto:hpohlmeyer@users.noreply.github.com) | git-stash: replace deprecated git stash save (#3077) | 2019-06-04T11:40:16 | [241e284db511](https://github.com/tldr-pages/tldr/commit/241e284db5114caa9dc356eb067e4e6482ea321a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Frank](mailto:frank.paczynski@solygen.de) | git stash: add clear (#1149) | 2016-11-19T18:43:18 | [8a23482bb622](https://github.com/tldr-pages/tldr/commit/8a23482bb6227cd3f64273468a17f32b6a2a96fc)
[kalebo](mailto:kaleb.olson@gmail.com) | git-stash: add -p option (#1094) | 2016-09-28T09:46:15 | [8dd53d6484d3](https://github.com/tldr-pages/tldr/commit/8dd53d6484d37540f6fe8f5edf69a0bed219eb0d)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | git-stash: Further improve verbosity of examples | 2016-09-02T14:33:17 | [2aca1c08b849](https://github.com/tldr-pages/tldr/commit/2aca1c08b8497951315d68e983b14273ab361865)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | git-stash: Improved examples verbosity | 2016-09-01T20:01:07 | [480255d59581](https://github.com/tldr-pages/tldr/commit/480255d59581842861f9485eeed95b44ec49c019)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | git-stash: Make examples clearer - Difference between a stash name and a stash message was not clear. For example, you cannot do: $ [...] | 2016-08-31T00:57:40 | [57fd36ec387e](https://github.com/tldr-pages/tldr/commit/57fd36ec387ee8482a45506e340b78152043ef84)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[André König](mailto:andre.koenig@posteo.de) | git-stash: Fixed command which is responsible for creating new stashes. | 2014-05-27T12:54:54 | [37d2d244a045](https://github.com/tldr-pages/tldr/commit/37d2d244a045d8fad6d55113c286df756105b72b)
[André König](mailto:andre.koenig@gmail.com) | Example for dropping a git stash. | 2014-05-24T22:05:35 | [6a3e6d2225b6](https://github.com/tldr-pages/tldr/commit/6a3e6d2225b642b77ea351df6f01b19151030ad9)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

