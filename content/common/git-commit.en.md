---
author: ['bagginslin', 'Simon Marcher', 'André Almeida', 'lord63', 'Dinesh', 'Marco Bonelli', 'Ruben Vereecken', 'Agniva De Sarker', 'kxy', 'CleanMachine1', 'Tan A', 'L Day', 'Ivan Aracki', 'Starbeamrainbowlabs', 'Te-Chi Liu']
date: 1626636503
title: "git commit, TLDR Pages"
description: "git commit, Commit files to the repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-commit>.

- Commit staged files to the repository with a message:

```bash
git commit -m "message"
```

- Commit staged files with a message read from a file:

```bash
git commit --file path/to/commit_message_file
```

- Auto stage all modified files and commit with a message:

```bash
git commit -a -m "message"
```

- Commit staged files and [S]ign them with the GPG key defined in `~/.gitconfig`:

```bash
git commit -S -m "message"
```

- Update the last commit by adding the currently staged changes, changing the commit's hash:

```bash
git commit --amend
```

- Commit only specific (already staged) files:

```bash
git commit path/to/file1 path/to/file2
```

- Create a commit, even if there are no staged files:

```bash
git commit -m "message" --allow-empty
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simon Marcher](mailto:marchersimon@zohomail.eu) | git-commit: add gpg-sign example | 2021-07-18T21:28:23 | [155df72786a5](https://github.com/tldr-pages/tldr/commit/155df72786a50f53ed1b75684e39d5664c64872e)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Update pages/common/git-commit.md Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> | 2021-06-10T22:01:58 | [c56a28bc7f9c](https://github.com/tldr-pages/tldr/commit/c56a28bc7f9cfe8b2d33cc21e1fd8184d8d52286)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-commit: add example | 2021-06-10T22:01:58 | [6814b4352b54](https://github.com/tldr-pages/tldr/commit/6814b4352b542d1cdb93b1e5bf5cabf5f05b29dc)
[bagginslin](mailto:51952061+bagginslin@users.noreply.github.com) | git-commit: add --file example (#5676) | 2021-04-04T14:59:11 | [84df3c982b6d](https://github.com/tldr-pages/tldr/commit/84df3c982b6d208123cda93bf23ff1cb4a17c058)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[André Almeida](mailto:andrealmeid@collabora.com) | git-commit: clarify amend example (#4703) | 2020-10-19T20:15:40 | [1d71ae134e1d](https://github.com/tldr-pages/tldr/commit/1d71ae134e1d1ee1e9f471a487f354098af4ed07)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | git commit: add example for committing specific files (#3090) | 2019-06-06T11:07:20 | [4057b76db696](https://github.com/tldr-pages/tldr/commit/4057b76db696ef36a5f5294b92cba64e1d458ca2)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[L Day](mailto:daylightbrightledlight@users.noreply.github.com) | git-commit: reorder commands (#2260) | 2018-08-27T11:29:23 | [0afa0fd3c21e](https://github.com/tldr-pages/tldr/commit/0afa0fd3c21ec7a0403cbc35d3ce4052acc2fb81)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Changing comment to message To better match with description | 2017-12-15T05:10:18 | [9eb1e4f686cf](https://github.com/tldr-pages/tldr/commit/9eb1e4f686cf6d409bc38156a8aad2ed44cc7d8f)
[Dinesh](mailto:flexdinesh@gmail.com) | git-commit: auto stage and commit | 2017-12-15T05:10:18 | [b7d0680fb354](https://github.com/tldr-pages/tldr/commit/b7d0680fb354fddece5e4c1d99600d452742ea10)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

