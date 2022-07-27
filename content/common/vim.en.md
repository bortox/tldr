---
author: ['Waldir Pimenta', 'L Day', 'Owen Voke', 'CARE-COLIN Thibaut', 'Leandro Ostera', 'Ryan Olson', 'Marco Bonelli', 'shoeletz', 'Alex Plescan', 'Ruben Vereecken', 'Ivan Miskovic', 'Jeroen Meulemeester', 'Eric Nielsen', 'CleanMachine1', 'Max Strübing', 'chris', 'marchersimon']
date: 1628945295
title: "vim, TLDR Pages"
description: "vim, Vim (Vi IMproved), a command-line text editor, provides several modes for different kinds of text manipulation."
categories: "common"
---
> Pressing `i` enters insert mode. `<Esc>` enters normal mode, which enables the use of Vim commands.

> More information: <https://www.vim.org>.

- Open a file:

```bash
vim path/to/file
```

- Open a file at a specified line number:

```bash
vim +line_number path/to/file
```

- View Vim's help manual:

```bash
:help<Enter>
```

- Save and Quit:

```bash
:wq<Enter>
```

- Undo the last operation:

```bash
u
```

- Search for a pattern in the file (press `n`/`N` to go to next/previous match):

```bash
/search_pattern<Enter>
```

- Perform a regular expression substitution in the whole file:

```bash
:%s/regular_expression/replacement/g<Enter>
```

- Display the line numbers:

```bash
:set nu<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[chris](mailto:35269695+chrissxYT@users.noreply.github.com) | vim: reorder examples (#6363) | 2021-08-14T14:48:15 | [e150609b4c24](https://github.com/tldr-pages/tldr/commit/e150609b4c248d4fa85ff9398bc397ad78122be5)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | vim: update description (#6237) | 2021-07-26T18:26:53 | [7eea9a22df3a](https://github.com/tldr-pages/tldr/commit/7eea9a22df3ac97037aaf6cc91e43f113e32df3c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | vim: add line numbers example (#4608) | 2020-10-31T21:42:18 | [591c38427555](https://github.com/tldr-pages/tldr/commit/591c38427555e8ff0ee9e05f0a2b04fc3ca47d3f)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | vim: move reference to accessing Vim's help up the list | 2020-01-30T01:59:51 | [11f895031530](https://github.com/tldr-pages/tldr/commit/11f895031530f6f0111040facef348d8addf5c41)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | vim: removed reference to "programmer's" text editor Vim can be used for all sorts of text editing. I know that there are a lot of [...] | 2020-01-30T01:59:51 | [dda02c001c12](https://github.com/tldr-pages/tldr/commit/dda02c001c128f8b52821755a9e82ff6df697445)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | vim: remove <ESC> from beginning of commands | 2020-01-30T01:59:51 | [e80c67e791bf](https://github.com/tldr-pages/tldr/commit/e80c67e791bff91662cf69e71887040a142355eb)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | vim: helpful additions Closes #3779 | 2020-01-30T01:59:51 | [2c40178eb1f0](https://github.com/tldr-pages/tldr/commit/2c40178eb1f089d12692a141af3a8d713f0c77ea)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[L Day](mailto:daylightbrightledlight@users.noreply.github.com) | vim: fix typo (#2265) | 2018-08-28T11:25:58 | [9bc8009b45ba](https://github.com/tldr-pages/tldr/commit/9bc8009b45ba2571b515b74533d4c0d6c86db8bc)
[Max Strübing](mailto:mxstrbng@gmail.com) | vim: remove wrongly description of % | 2017-10-21T22:01:49 | [666f312e2bff](https://github.com/tldr-pages/tldr/commit/666f312e2bff870a2a0cf83226f197450bae17bf)
[Max Strübing](mailto:mxstrbng@gmail.com) | vim: add s for substitution | 2017-10-19T19:27:18 | [c4a0fbd89ef6](https://github.com/tldr-pages/tldr/commit/c4a0fbd89ef6f1058d8bfebd64e2830ff77233a1)
[Max Strübing](mailto:struebing@sitegeist.de) | vim: simplify substitution in whole file | 2017-10-19T14:38:46 | [37fa82919bd8](https://github.com/tldr-pages/tldr/commit/37fa82919bd815a5602d3d604ab8e141deac12f3)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | vim: Normal mode is the normal mode (#1106) * vim: Improvements we can can agree on Remove spaces between keypresses (as it could lead [...] | 2016-10-12T05:28:21 | [8d93237d6361](https://github.com/tldr-pages/tldr/commit/8d93237d63619b68edebb591f9d766d326e4a2d3)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | vim: improve examples (#1105) I tried to condense the most useful basic commands into this page without surpassing our length limit. I [...] | 2016-10-06T12:19:06 | [4b7ef4a18d06](https://github.com/tldr-pages/tldr/commit/4b7ef4a18d06d57510422f656650d6e67c68b5f6)
[Leandro Ostera](mailto:leandro@ostera.io) | Updates vim and vimtutor pages (#926) * Updates vim and vimtutor pages * Easy peasy. * Use <Enter> instead of <Cr> * Show help [...] | 2016-08-21T16:00:09 | [2ba4397edc71](https://github.com/tldr-pages/tldr/commit/2ba4397edc711cf3f599990af47710c3e74e93e6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | vim.md: apply fix per code review comments | 2016-08-06T15:34:25 | [4732cbbc9347](https://github.com/tldr-pages/tldr/commit/4732cbbc934795de18f38af6464cedd27ab24d79)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | vim.md: apply formatting conventions | 2016-08-06T15:29:34 | [1f0970401fc0](https://github.com/tldr-pages/tldr/commit/1f0970401fc01544e3c37ccdb35b3c62c0fe2444)
[shoeletz](mailto:adam.sulucz@gmail.com) | reduced repetetiveness of descriptions | 2016-08-06T15:28:12 | [abcdb8dee25f](https://github.com/tldr-pages/tldr/commit/abcdb8dee25f586a5744b1c196ef74732a68c203)
[shoeletz](mailto:adam.sulucz@gmail.com) | Update vim.md | 2016-08-06T15:25:00 | [5adbb1fa34b3](https://github.com/tldr-pages/tldr/commit/5adbb1fa34b3afe3b7aa8adde83d321bd07e5e1e)
[shoeletz](mailto:adam.sulucz@gmail.com) | vim: add :w, :wq, i | 2016-08-06T15:24:14 | [314a240945a8](https://github.com/tldr-pages/tldr/commit/314a240945a8ebeff07c51042fed3a5139f6a72d)
[Alex Plescan](mailto:alexpls@gmail.com) | vim: fix typo | 2016-08-02T02:56:07 | [9ae27f3ea27f](https://github.com/tldr-pages/tldr/commit/9ae27f3ea27f92329bb0ca8166a28642ec28fcfa)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ivan Miskovic](mailto:ivan@patentpending.co.nz) | vim doc grammar fix Changed `a programmers text editor` to `a programmer's text editor` | 2016-01-05T01:29:24 | [38de59f8cd2e](https://github.com/tldr-pages/tldr/commit/38de59f8cd2e8b8f65bddd204b3b441c5e8fe1af)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | Add pages for vim and vimtutor | 2015-12-28T13:38:25 | [7f08ffc5a3ec](https://github.com/tldr-pages/tldr/commit/7f08ffc5a3ec074b82f57c7756b4af0529cc64cf)

