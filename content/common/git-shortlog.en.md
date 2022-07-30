---
author: ['Starbeamrainbowlabs', 'Marco Bonelli', 'bl-ue', 'Ivan Aracki', 'thescalaguy']
date: 1607722048
title: "git shortlog"
description: "git shortlog, Summarizes the `git log` output."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-shortlog>.

- View a summary of all the commits made, grouped alphabetically by author name:

```bash
git shortlog
```

- View a summary of all the commits made, sorted by the number of commits made:

```bash
git shortlog -n
```

- View a summary of all the commits made, grouped by the committer identities (name and email):

```bash
git shortlog -c
```

- View a summary of the last 5 commits (i.e. specify a revision range):

```bash
git shortlog HEAD~5..HEAD
```

- View all users, emails and the number of commits in the current branch:

```bash
git shortlog -sne
```

- View all users, emails and the number of commits in all branches:

```bash
git shortlog -sne --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | git-shortlog: add -sne commands (#3213) | 2019-07-31T05:18:58 | [8c9a70a95708](https://github.com/tldr-pages/tldr/commit/8c9a70a957086b671f0cc12cd789f222eefe917c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[thescalaguy](mailto:fasihxkhatib@gmail.com) | git-shortlog: add page (#2044) | 2018-03-27T09:29:00 | [da60c8edb1f7](https://github.com/tldr-pages/tldr/commit/da60c8edb1f7da368af6e9ea4cdab6b83ec8a2c7)

