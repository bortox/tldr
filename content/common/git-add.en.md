---
author: ['Parth Mehrotra', 'Srinivasan R', 'lord63', 'Seth Woodworth', 'Ryan Olson', 'Marco Bonelli', 'Ruben Vereecken', 'kxy', 'Ein Verne', 'Starbeamrainbowlabs', 'Markus Thoemmes']
date: 1586968525
title: "git add, TLDR Pages"
description: "git add, Adds changed files to the index."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-add>.

- Add a file to the index:

```bash
git add path/to/file
```

- Add all files (tracked and untracked):

```bash
git add -A
```

- Only add already tracked files:

```bash
git add -u
```

- Also add ignored files:

```bash
git add -f
```

- Interactively stage parts of files:

```bash
git add -p
```

- Interactively stage parts of a given file:

```bash
git add -p path/to/file
```

- Interactively stage a file:

```bash
git add -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | git-stage: add page (#3963) * git-stage: add page * Apply suggestions from code review Co-Authored-By: Starbeamrainbowlabs [...] | 2020-04-15T18:35:25 | [955a6b7b5428](https://github.com/tldr-pages/tldr/commit/955a6b7b5428b26899db274cd8d745933175364e)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | git-add: add git add interactively for all changed files (#3778) | 2020-01-23T11:24:01 | [3b017c80e7da](https://github.com/tldr-pages/tldr/commit/3b017c80e7da5334bc5c7142b2a96d1036ebafda)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Parth Mehrotra](mailto:parth.mehrotra.cs@gmail.com) | git-add: update to -A option (#1051) See: (`git add -A` vs `git add .`)[http://stackoverflow.com/questions/26042390/git-add-asterisk- [...] | 2016-09-12T06:23:57 | [4bfdfacfa73b](https://github.com/tldr-pages/tldr/commit/4bfdfacfa73b9a7e532c572e2d6b2d515dd3bcbe)
[Seth Woodworth](mailto:seth@sethish.com) | Adds git-add -p instructions | 2016-01-28T15:37:49 | [669251821348](https://github.com/tldr-pages/tldr/commit/6692518213481fdfbc8c0493bbfa450bf8081104)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Markus Thoemmes](mailto:markusthoemmes@me.com) | Adding git add -u | 2015-12-27T21:46:25 | [6dae21d33558](https://github.com/tldr-pages/tldr/commit/6dae21d335588c18230179b15b3f1e4c63a7c2a0)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

