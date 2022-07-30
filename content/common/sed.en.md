---
author: ['Amine Hajyoussef', 'Waldir Pimenta', 'Igor Shubovych', 'James H. Linder', 'Khaja Minhajuddin', 'git-em', 'mira01', 'Lucas Gabriel Schneider', 'rprieto', 'Srinivasan R', 'Ray Voice', 'Timothée Mazzucotelli', 'Marco Bonelli', 'Ruben Vereecken', "James O'Beirne", 'Leandro Ostera', 'Seth Falco', 'marchersimon']
date: 1646800137
title: "sed"
description: "sed, Edit text in a scriptable manner."
categories: "common"
---
> More information: <https://www.gnu.org/software/sed/manual/sed.html>.

- Replace the first occurrence of a regular expression in each line of a file, and print the result:

```bash
sed 's/regular_expression/replace/' filename
```

- Replace all occurrences of an extended regular expression in a file, and print the result:

```bash
sed -r 's/regular_expression/replace/g' filename
```

- Replace all occurrences of a string in a file, overwriting the file (i.e. in-place):

```bash
sed -i 's/find/replace/g' filename
```

- Replace only on lines matching the line pattern:

```bash
sed '/line_pattern/s/find/replace/' filename
```

- Delete lines matching the line pattern:

```bash
sed '/line_pattern/d' filename
```

- Print the first 11 lines of a file:

```bash
sed 11q filename
```

- Apply multiple find-replace expressions to a file:

```bash
sed -e 's/find/replace/' -e 's/find/replace/' filename
```

- Replace separator `/` by any other character not used in the find or replace patterns, e.g. `#`:

```bash
sed 's#find#replace#' filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | common/sed: add link (#5534) | 2021-03-30T10:59:06 | [e69a9eed3557](https://github.com/tldr-pages/tldr/commit/e69a9eed35577583e840d6c39a44927f15d31eb3)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | sed: add 11q example (#4399) | 2020-10-12T23:53:52 | [40a910e6cfbc](https://github.com/tldr-pages/tldr/commit/40a910e6cfbcd7dbdcea58a69cdc999233450816)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | sed: minor syntax fix | 2019-04-09T06:04:48 | [e75baf7d7388](https://github.com/tldr-pages/tldr/commit/e75baf7d7388c4670c518c190a4ccf535bc8fbff)
[James O'Beirne](mailto:james@chaincode.com) | sed: get nth line of a file | 2019-04-09T06:04:48 | [06942171bdc0](https://github.com/tldr-pages/tldr/commit/06942171bdc01591e4e9f18acb42ecc05ff4cbe2)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | sed: fix misleading examples description. (#2685) | 2019-01-08T19:28:59 | [cbe477bf5003](https://github.com/tldr-pages/tldr/commit/cbe477bf5003c00e4f00a466ed0c608dc394840b)
[Timothée Mazzucotelli](mailto:pawamoy@pm.me) | sed: Add example to delete lines (#2596) | 2018-11-16T15:11:22 | [7d23961ac3e5](https://github.com/tldr-pages/tldr/commit/7d23961ac3e593f2742e9f773688eed46f82ca48)
[mira01](mailto:miracech@email.cz) | sed: show usage of a print command (#2154) | 2018-06-26T17:19:31 | [10ae4c757394](https://github.com/tldr-pages/tldr/commit/10ae4c7573943e0a3628b72dbf538d215759567b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed.md: add input to the only example missing it (#992) * sed.md: add input to the only example missing it * osx/sed.md: add input to [...] | 2016-08-08T09:09:34 | [a1ceb9d1b6e1](https://github.com/tldr-pages/tldr/commit/a1ceb9d1b6e12f7b0b774c166e3e028d4fe11c64)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed: swap extended regex & line pattern examples | 2016-04-21T20:13:01 | [685b6ea8bd99](https://github.com/tldr-pages/tldr/commit/685b6ea8bd99e71d1c645e5b9bc374d490022776)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sed: reword last example and add it to the osx version too | 2016-04-21T20:11:33 | [1c76b8ea7be0](https://github.com/tldr-pages/tldr/commit/1c76b8ea7be08498f82d44b049e78ca528173493)
[Khaja Minhajuddin](mailto:minhajuddin.k@gmail.com) | sed.md: use alternative separators (#806) | 2016-04-10T21:18:24 | [4915aa3b8b92](https://github.com/tldr-pages/tldr/commit/4915aa3b8b92492384f1a10c936c4e52b70b47b6)
[Leandro Ostera](mailto:leandro@ostera.io) | Updates description | 2016-03-01T12:54:15 | [e22f8087e10a](https://github.com/tldr-pages/tldr/commit/e22f8087e10a77ecddb52de4cde50b8ac37a114d)
[Leandro Ostera](mailto:leandro@ostera.io) | Sed: adds replace before matching sample Something I find myself doing more and more is to match on a line instead of trying to match [...] | 2016-02-27T14:23:24 | [7328774d81bf](https://github.com/tldr-pages/tldr/commit/7328774d81bf8feef6d6ff00f8cbb6ba8300c46e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted sed page | 2016-01-21T13:02:00 | [4a52a7006d20](https://github.com/tldr-pages/tldr/commit/4a52a7006d20516b9f232af136212e2b58240cbd)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'patch-3' of git://github.com/waldyrious/tldr into waldyrious-patch-3 Conflicts: pages/common/sed.md | 2016-01-21T13:01:04 | [a454ee1a5d71](https://github.com/tldr-pages/tldr/commit/a454ee1a5d71b451ae110018ac89bb91420ef72c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | consistent markup | 2015-12-31T14:11:18 | [3fe8681e19ac](https://github.com/tldr-pages/tldr/commit/3fe8681e19acf79351509fb46b1988a0ab64397f)
[Leandro Ostera](mailto:leandro@ostera.io) | Update sed.md Error on the command. | 2015-11-23T16:05:25 | [1a75ffb92a14](https://github.com/tldr-pages/tldr/commit/1a75ffb92a14cd66a08a80db10bdca518be38af3)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | restore short option -i per discussion in #293 | 2015-08-25T01:56:09 | [a92aec7dc09f](https://github.com/tldr-pages/tldr/commit/a92aec7dc09f9c6e2eeb3d0d9bc3bd9db4f65b8b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | various fixes and tweaks to sed - don't use g in all examples - fix option for extended regex (-E is in grep :)) - spell out the -i [...] | 2015-08-20T17:59:41 | [0348a644de6d](https://github.com/tldr-pages/tldr/commit/0348a644de6d6907e8e5b136dc68027a759898db)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | sed: fix md syntax | 2014-05-18T00:12:37 | [27be7514788e](https://github.com/tldr-pages/tldr/commit/27be7514788e3d92adbefcf103c2330419c2738c)
[James H. Linder](mailto:james@jlinder.com) | Adding a line for sed for making multiple replacements in one command. | 2014-03-27T19:27:35 | [1efb6b906d3c](https://github.com/tldr-pages/tldr/commit/1efb6b906d3c152ab634c9ee2d1fa0d2bd94bad3)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

