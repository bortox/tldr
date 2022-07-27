---
author: ['lord63', 'rprieto', 'Marco Bonelli', 'Ruben Vereecken', 'pxgamer', 'Guido Lena Cota', 'bl-ue', 'Hugo Locurcio']
date: 1621541621
title: "svn, TLDR Pages"
description: "svn, Subversion command-line client tool."
categories: "common"
---
> More information: <https://subversion.apache.org>.

- Check out a working copy from a repository:

```bash
svn co url/to/repository
```

- Bring changes from the repository into the working copy:

```bash
svn up
```

- Put files and directories under version control, scheduling them for addition to repository. They will be added in next commit:

```bash
svn add PATH
```

- Send changes from your working copy to the repository:

```bash
svn ci -m commit_log_message [PATH]
```

- Display changes from the last 10 revisions, showing modified files for each revision:

```bash
svn log -vl 10
```

- Show detailed help:

```bash
svn help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | svn: add link to homepage | 2019-05-14T19:58:59 | [5df3d2255f74](https://github.com/tldr-pages/tldr/commit/5df3d2255f74785852694c5e3b247c00b77ad4bb)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | 7z, 7za, svn: remove unneeded ellipsis. svn: remove unneeded ellipsis. | 2019-02-03T04:27:37 | [24ff2872510f](https://github.com/tldr-pages/tldr/commit/24ff2872510f7bfac1e82fc333d8b928a8c50a0e)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | svn: add log example (#2565) | 2018-11-08T20:15:18 | [738c6e301304](https://github.com/tldr-pages/tldr/commit/738c6e301304c25d0ab2f8ba97fa1ae7cb0a6273)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

