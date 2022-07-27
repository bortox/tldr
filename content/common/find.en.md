---
author: ['wai4y', 'Cvetomird91', 'Agniva De Sarker', 'kongmoumou', 'Alexander Berezovsky', 'Tan Shuai', 'Cornelius Mika', 'Xiang Wang', 'Ruben Vereecken', 'Rodrigo Orem', 'Fazle Arefin', 'Rajiv Nair', 'rprieto', 'marchersimon', 'Waldir Pimenta', 'Eliot Sykes', 'Surkal', 'Eric Nielsen', 'dwdh', 'Alfred Bez', 'Bo-Yi Wu']
date: 1631303193
title: "find, TLDR Pages"
description: "find, Find files or directories under the given directory tree, recursively."
categories: "common"
---
> More information: <https://manned.org/find>.

- Find files by extension:

```bash
find root_path -name '*.ext'
```

- Find files matching multiple path/name patterns:

```bash
find root_path -path '**/path/**/*.ext' -or -name '*pattern*'
```

- Find directories matching a given name, in case-insensitive mode:

```bash
find root_path -type d -iname '*lib*'
```

- Find files matching a given pattern, excluding specific paths:

```bash
find root_path -name '*.py' -not -path '*/site-packages/*'
```

- Find files matching a given size range:

```bash
find root_path -size +500k -size -10M
```

- Run a command for each file (use `{}` within the command to access the filename):

```bash
find root_path -name '*.ext' -exec wc -l {} \;
```

- Find files modified in the last 7 days and delete them:

```bash
find root_path -daystart -mtime -7 -delete
```

- Find empty (0 byte) files and delete them:

```bash
find root_path -type f -empty -delete
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dwdh](mailto:35333274+dwdh@users.noreply.github.com) | find: add -daystart option (#6499) | 2021-09-10T21:46:33 | [0e0dc204b25c](https://github.com/tldr-pages/tldr/commit/0e0dc204b25c28b99e2d2c41f92534384fa9e674)
[wai4y](mailto:dehp520@gmail.com) | find: closing single quote missed in example (#6410) | 2021-08-25T17:45:40 | [2ffb8c96d336](https://github.com/tldr-pages/tldr/commit/2ffb8c96d3362c4e441a7520c689a51c5f245880)
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | find: add example to find and delete empty files (#5973) | 2021-05-16T21:06:51 | [a81bad6485ec](https://github.com/tldr-pages/tldr/commit/a81bad6485ec5bd7e98fc8a44d0f5e163a152ca2)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[kongmoumou](mailto:35442047+kongmoumou@users.noreply.github.com) | find: always enclose the pattern in quotes (#3983) As mentioned in man page, should always enclose the pattern in quotes in order to [...] | 2020-04-15T18:51:26 | [d5c3d824c5d0](https://github.com/tldr-pages/tldr/commit/d5c3d824c5d0e063235c72720832b1faa856fbe5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | find: various improvements (#3124) * find: various improvements The information content of the page should be unchanged, but hopefully [...] | 2019-06-24T04:43:25 | [261abcdd90ec](https://github.com/tldr-pages/tldr/commit/261abcdd90ecc1afd9fbcf18f7faa3345e84169f)
[Alexander Berezovsky](mailto:42983344+ab-pivot@users.noreply.github.com) | find: add searching multiple patterns simultaneously (#2589) | 2018-11-15T22:33:41 | [3a97f27dbeeb](https://github.com/tldr-pages/tldr/commit/3a97f27dbeeb7816e52b381fbab8fc0e5f6a38ec)
[Surkal](mailto:Surkal@users.noreply.github.com) | fix argument | 2018-10-07T06:19:11 | [032dd82ce19c](https://github.com/tldr-pages/tldr/commit/032dd82ce19cdcc1a28dd236bd1d8965d508ef48)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | find: reoder example | 2018-08-27T10:10:39 | [b16fa9f0fa74](https://github.com/tldr-pages/tldr/commit/b16fa9f0fa74adc0d9e493e7e037e820962a2018)
[Rodrigo Orem](mailto:rodorgas@users.noreply.github.com) | find: remove the -or conditional entry Due to the limit of 8 entries, we need to remove one entry to add the search by directory name. [...] | 2018-08-27T10:10:39 | [d3d91a5804ab](https://github.com/tldr-pages/tldr/commit/d3d91a5804ab5dae115027105d27503323935e9e)
[Rodrigo Orem](mailto:rodorgas@users.noreply.github.com) | find: add directory search | 2018-08-27T10:10:39 | [8ef91a1e7156](https://github.com/tldr-pages/tldr/commit/8ef91a1e71566b4cc03dc7e5e1ebb660f38bbd9f)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | find: add unit for mtime Clarifying that mtime stands for no. of days | 2017-12-30T20:43:15 | [1e8f60f7cdd4](https://github.com/tldr-pages/tldr/commit/1e8f60f7cdd4df2969f587e3f8650f034debbdd2)
[Tan Shuai](mailto:7anshuai@gmail.com) | find: fix -mtime example (#1625) | 2017-11-08T20:39:07 | [abaabe35caee](https://github.com/tldr-pages/tldr/commit/abaabe35caee3f39882927db8dfcc5ad37a8c13a)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | find: improve -mtime example Make the description clearer and more specific to the given `-1` parameter. Remove unnecessary `-name [...] | 2017-10-05T23:23:30 | [b0b440436f5a](https://github.com/tldr-pages/tldr/commit/b0b440436f5a575c58e8d23b826fce02b83ab7a7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | find: slightly reword the -not -path example | 2017-04-25T23:50:51 | [cd38a006d8a3](https://github.com/tldr-pages/tldr/commit/cd38a006d8a3664b3fcfcb57dac0beb43ed86698)
[Xiang Wang](mailto:ramwin@qq.com) | find: ignore given directory (#1289) * find path while excluding certain directory * delete the `find {{root_path}} -empty` command to [...] | 2017-03-10T15:48:29 | [462673502121](https://github.com/tldr-pages/tldr/commit/462673502121d901e11e0fcb28cf14fb9942cd6d)
[Alfred Bez](mailto:alfred.bez@googlemail.com) | mtime argument (find command) expect numeric value | 2017-03-10T05:43:34 | [cd29c9775f92](https://github.com/tldr-pages/tldr/commit/cd29c9775f92647b1160e3a587e3db4d78230538)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | find: quotes outside tokens; generic extension (#1160) The generic extension is to conform to our contribution guidelines: [...] | 2016-11-26T16:51:12 | [63659bed3706](https://github.com/tldr-pages/tldr/commit/63659bed3706ff60b3f17faafa4a7d8a0232acbc)
[Cornelius Mika](mailto:cornelius.mika@gmail.com) | Fix argument quoting | 2016-02-24T10:27:51 | [e019c18cdd86](https://github.com/tldr-pages/tldr/commit/e019c18cdd86e7cdd4ff343fa4caf29b0a276c92)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted find page | 2016-01-21T13:12:53 | [0ba869a5fcaa](https://github.com/tldr-pages/tldr/commit/0ba869a5fcaabdae569b28097111b2741c32a979)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'find' of git://github.com/Cvetomird91/tldr into Cvetomird91-find | 2016-01-21T13:12:28 | [38068377beb7](https://github.com/tldr-pages/tldr/commit/38068377beb7d427ef99f3311230587a4f10113a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Cvetomird91](mailto:cvetomirdenchev@gmail.com) | find: added options for multiple search criteria and empty files added path for -empty option | 2015-12-31T11:20:17 | [f3e3035de74a](https://github.com/tldr-pages/tldr/commit/f3e3035de74aa56d9aea78b6d53bf9c62575ca26)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | find -path option | 2015-12-28T19:06:08 | [2038fc0f13c3](https://github.com/tldr-pages/tldr/commit/2038fc0f13c33a985501095163f5486e332d81bd)
[Bo-Yi Wu](mailto:appleboy.tw@gmail.com) | Update find.md | 2015-12-28T10:43:58 | [ed380d1a67c6](https://github.com/tldr-pages/tldr/commit/ed380d1a67c68990dcf668e1eec51b9437af586e)
[Bo-Yi Wu](mailto:appleboy.tw@gmail.com) | remove unnecessary example. | 2015-12-28T06:28:26 | [c97b72992417](https://github.com/tldr-pages/tldr/commit/c97b72992417d99e10bfcc298c94f60500cc1bd9)
[Rajiv Nair](mailto:rnair@rnair.local) | Add find -delete | 2015-12-27T19:02:02 | [c92cd2281ebf](https://github.com/tldr-pages/tldr/commit/c92cd2281ebfbbd4983bf9de1e46b6b8a5ecfe72)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

