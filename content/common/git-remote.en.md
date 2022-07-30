---
author: ['Waldir Pimenta', 'Lampros Mountrakis', 'lord63', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Jorge A. Borges', 'Ruben Vereecken', 'Ann Cascarano']
date: 1586969542
title: "git remote"
description: "git remote, Manage set of tracked repositories ('remotes')."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-remote>.

- Show a list of existing remotes, their names and URL:

```bash
git remote -v
```

- Show information about a remote:

```bash
git remote show remote_name
```

- Add a remote:

```bash
git remote add remote_name remote_url
```

- Change the URL of a remote (use `--add` to keep the existing URL):

```bash
git remote set-url remote_name new_url
```

- Remove a remote:

```bash
git remote remove remote_name
```

- Rename a remote:

```bash
git remote rename old_name new_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ann Cascarano](mailto:4411121+redrambles@users.noreply.github.com) | git-remote: add command (#3982) | 2020-04-15T18:52:22 | [1f1c9e035743](https://github.com/tldr-pages/tldr/commit/1f1c9e03574370b5d2c97cd4c93be720f5720197)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-remote: mention how to add a new URL (#3042) | 2019-05-20T14:52:55 | [2d7a0b034c26](https://github.com/tldr-pages/tldr/commit/2d7a0b034c2614d032a56fd7271c61e3399977a6)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Lampros Mountrakis](mailto:lmount@users.noreply.github.com) | git-remote: use straight quotation marks instead of curly ones (#951) this was the only command page that used non-ASCII characters | 2016-07-14T09:18:38 | [d8a221ef26f2](https://github.com/tldr-pages/tldr/commit/d8a221ef26f21c30481efc094b204eab01669830)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Jorge A. Borges](mailto:contact@jorgeborges.me) | Adding git remote set-url example, removing git remote add and fetch | 2015-03-30T14:20:14 | [f7828563b0eb](https://github.com/tldr-pages/tldr/commit/f7828563b0eba1b4fb7f9bfcf58a13d33f444447)
[Jorge A. Borges](mailto:contact@jorgeborges.me) | Add git remote | 2015-03-30T13:45:48 | [779407e76ff3](https://github.com/tldr-pages/tldr/commit/779407e76ff3cb439f27d1ae5510acba848c2676)

