---
author: ['quarcu', 'Paul S', 'shyneko', 'Arvid Gerstmann', 'Guido Lena Cota', 'Toon Nolten', 'Ruben Vereecken', 'Sven-Hendrik Haase', 'bl-ue', 'Matt Ross', 'Bart Nagel', 'Daniel Jour', 'pxgamer', 'rprieto', 'Waldir Pimenta', 'Simon Erkelens', "Robby O'Connor", 'Marco Bonelli', 'Jeong Arm', 'Joshua']
date: 1620114251
title: "tar, TLDR Pages"
description: "tar, Archiving utility."
categories: "common"
---
> Often combined with a compression method, such as gzip or bzip2.

> More information: <https://www.gnu.org/software/tar>.

- [c]reate an archive and write it to a [f]ile:

```bash
tar cf target.tar file1 file2 file3
```

- [c]reate a g[z]ipped archive and write it to a [f]ile:

```bash
tar czf target.tar.gz file1 file2 file3
```

- [c]reate a g[z]ipped archive from a directory using relative paths:

```bash
tar czf target.tar.gz --directory=path/to/directory .
```

- E[x]tract a (compressed) archive [f]ile into the current directory [v]erbosely:

```bash
tar xvf source.tar[.gz|.bz2|.xz]
```

- E[x]tract a (compressed) archive [f]ile into the target directory:

```bash
tar xf source.tar[.gz|.bz2|.xz] --directory=directory
```

- [c]reate a compressed archive and write it to a [f]ile, using [a]rchive suffix to determine the compression program:

```bash
tar caf target.tar.xz file1 file2 file3
```

- Lis[t] the contents of a tar [f]ile [v]erbosely:

```bash
tar tvf source.tar
```

- E[x]tract files matching a pattern from an archive [f]ile:

```bash
tar xf source.tar --wildcards "*.html"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bart Nagel](mailto:bart@tremby.net) | tar: add "verbose" to another example (#5860) | 2021-05-04T09:44:11 | [75b5a8da0abf](https://github.com/tldr-pages/tldr/commit/75b5a8da0abf60282ff187e91363732aaec5c6c1)
[Bart Nagel](mailto:bart@tremby.net) | tar: fix mnemonic for f (#5859) Before this patch the document suggested that the `f` allows the user to list some files to extract or [...] | 2021-05-01T20:46:55 | [69887e9d26d3](https://github.com/tldr-pages/tldr/commit/69887e9d26d3cd4bab819ff8027aa2f1c5ba48aa)
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | tar: add brackets explaining mnemonics (#5083) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-04T19:06:54 | [f72524cdb268](https://github.com/tldr-pages/tldr/commit/f72524cdb2684eb3fc4c9e6de8bad932832515d1)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | tar: remove last example to reduce count to 8 (#5078) | 2021-01-04T01:23:25 | [40120a4cc8d4](https://github.com/tldr-pages/tldr/commit/40120a4cc8d4b354bd046ef2386cbddd0d55f53f)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[shyneko](mailto:34548743+tminei@users.noreply.github.com) | tar: update an example (#4230) | 2020-07-28T16:27:36 | [a9d0095fddd9](https://github.com/tldr-pages/tldr/commit/a9d0095fddd9919e6bbc0cd0dc9fd141b8f92231)
[Simon Erkelens](mailto:github@casa-laguna.net) | Tar: Add extraction of file without folder structure (#3859) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-03-24T12:53:00 | [f6022ded6ce0](https://github.com/tldr-pages/tldr/commit/f6022ded6ce00bb891cf533e5c361f38ea468ec2)
[Paul S](mailto:pshirshov@gmail.com) | tar: add a relative paths example (#3867) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-02-25T20:04:41 | [bb264b81b2a7](https://github.com/tldr-pages/tldr/commit/bb264b81b2a77998380a1eb1f0a9442d2c53b1f3)
[Joshua](mailto:Joshua.Doll@online.de) | tar: update multiple file tokens | 2019-10-21T18:56:56 | [4d8a24c6a53e](https://github.com/tldr-pages/tldr/commit/4d8a24c6a53eee8544295e6fe5110cfab84d7080)
[Toon Nolten](mailto:toonn@toonn.io) | tar: simplify extraction examples (#3336) Dropped the examples for extraction of specific compressed archives, tar has had [...] | 2019-10-10T19:28:46 | [7904a322f200](https://github.com/tldr-pages/tldr/commit/7904a322f2004e1203bb834b95b4001b4b9d86b3)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tar: add link to homepage | 2019-05-14T19:58:59 | [e0a57e00b647](https://github.com/tldr-pages/tldr/commit/e0a57e00b6474231c6a1793d81287eb98f9f8604)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Jeong Arm](mailto:kjwonmail@gmail.com) | tar: add hyphen for flags (#2637) | 2019-01-28T19:44:44 | [4f08cc485d2e](https://github.com/tldr-pages/tldr/commit/4f08cc485d2eb57fdfb6c64a126220dc21785a7e)
[Matt Ross](mailto:amsross@users.noreply.github.com) | tar: extract files matching a pattern (#1883) | 2018-01-14T13:41:22 | [31e256b4578c](https://github.com/tldr-pages/tldr/commit/31e256b4578c1a91ed110fbb13c13005922ccda8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tar: reword the second sentence of the main desc. (#1058) | 2016-09-22T21:09:54 | [d7041ec1d3ef](https://github.com/tldr-pages/tldr/commit/d7041ec1d3ef65f14012ff1bba209430e57876de)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Sven-Hendrik Haase](mailto:svenstaro@gmail.com) | Make tar page consistent It might confuse users if everything has no dash in front but the last command does. tar doesn't need the [...] | 2015-12-29T09:25:39 | [6b906eae18f9](https://github.com/tldr-pages/tldr/commit/6b906eae18f9e1f8e5133f2628fa4b63d9d134a1)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix typo: "programm" --> "program" | 2015-03-02T10:06:40 | [6dd3e1811095](https://github.com/tldr-pages/tldr/commit/6dd3e18110958254d8d936bed96e4d8ac96d5b76)
[quarcu](mailto:quarcu@users.noreply.github.com) | List content of tar file List content of tar file. I recommend reducing amount of options regarding compressed files since on some OS [...] | 2014-09-10T01:45:57 | [09c2d6692333](https://github.com/tldr-pages/tldr/commit/09c2d6692333416977f68502c6e85776b40a3910)
[Daniel Jour](mailto:Daniel.Oertwig@googlemail.com) | automatic compression selection for tar Using a instead of z,j,J ... makes it easy to use different compression programms | 2014-09-04T10:44:00 | [36191abc1813](https://github.com/tldr-pages/tldr/commit/36191abc18133814cc1c0e1eb0a424f46444fdda)
[Arvid Gerstmann](mailto:dev@arvid-g.de) | add extraction of bzipped archive | 2014-04-23T20:35:39 | [8ef2a8aff345](https://github.com/tldr-pages/tldr/commit/8ef2a8aff34573dd0adeb81a1ce16868278fddda)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

