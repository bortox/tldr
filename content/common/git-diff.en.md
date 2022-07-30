---
author: ['Waldir Pimenta', 'Frank', 'Agniva De Sarker', 'kxy', 'Zlatan Vasović', 'Eric Sirianni', 'lord63', 'Timo Sand', 'jitakirin', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Eliot Sykes', 'Mateu Aguiló Bosch', 'zdroid', 'Ruben Vereecken']
date: 1595473581
title: "git diff"
description: "git diff, Show changes to tracked files."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-diff>.

- Show unstaged, uncommitted changes:

```bash
git diff
```

- Show all uncommitted changes (including staged ones):

```bash
git diff HEAD
```

- Show only staged (added, but not yet committed) changes:

```bash
git diff --staged
```

- Show changes from all commits since a given date/time (a date expression, e.g. "1 week 2 days" or an ISO date):

```bash
git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}'
```

- Show only names of changed files since a given commit:

```bash
git diff --name-only commit
```

- Output a summary of file creations, renames and mode changes since a given commit:

```bash
git diff --summary commit
```

- Compare a single file between two branches or commits:

```bash
git diff branch_1..branch_2 [--] path/to/file
```

- Compare different files from the current branch to other branch:

```bash
git diff branch:path/to/file2 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | git-diff: remove 9th example (#4204) | 2020-07-23T05:06:21 | [0f879b604921](https://github.com/tldr-pages/tldr/commit/0f879b6049212a9e81396c345252a0a707f988d0)
[zdroid](mailto:zlatanvasovic@gmail.com) | Revert "git-diff: remove 9th example" This reverts commit d31091d9377a79f80940adee753910a86ab6f997. | 2020-07-17T19:59:43 | [700b238b9799](https://github.com/tldr-pages/tldr/commit/700b238b9799532fcae29e7209add12007d6b62b)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | git-diff: remove 9th example Closes #3753. | 2020-07-17T19:58:11 | [d31091d9377a](https://github.com/tldr-pages/tldr/commit/d31091d9377a79f80940adee753910a86ab6f997)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Timo Sand](mailto:timo.sand@iki.fi) | git-diff: Adds comparison of file on current branch to other branch (#1611) | 2017-11-04T10:31:27 | [c6eaf3ae242f](https://github.com/tldr-pages/tldr/commit/c6eaf3ae242f0ba5eea595bd87ddb89d919826cc)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | git-diff: update description Replace backticks with quotes | 2017-11-02T05:17:47 | [dbff7a26f7f9](https://github.com/tldr-pages/tldr/commit/dbff7a26f7f9db8fbe7e3b9abc2bc6bfd047c4c4)
[jitakirin](mailto:jitakirin@gmail.com) | git-diff: update examples to show other possibilities Show that date expression/spec can contain other items and combinations of [...] | 2017-11-01T08:07:23 | [29bae17f8cc3](https://github.com/tldr-pages/tldr/commit/29bae17f8cc318debd9fc91e715d978fbce64c9b)
[jitakirin](mailto:jitakirin@gmail.com) | git-diff: add example using relative time range Close #1368 | 2017-10-31T23:32:16 | [a33f630def56](https://github.com/tldr-pages/tldr/commit/a33f630def569a66d7163ff0d4a1ed6d310a2245)
[Eric Sirianni](mailto:sirianni@users.noreply.github.com) | git-diff: add cross-branch diff example (#1454) | 2017-08-25T13:42:05 | [91d54f868e29](https://github.com/tldr-pages/tldr/commit/91d54f868e29ab10c72353728b2585dcecc63849)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-diff: rework a bit for clarity (#1129) - use {{commit}} instead of {{PATHSPEC}} - start with the simplest invocation, git diff - [...] | 2016-10-27T18:15:29 | [b2401cf0be9a](https://github.com/tldr-pages/tldr/commit/b2401cf0be9af4ffa9ac8f8f458e20baf6639175)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Frank](mailto:frank.paczynski@solygen.de) | git-diff: create a patch file | 2016-06-17T13:08:01 | [6bdd183e86f3](https://github.com/tldr-pages/tldr/commit/6bdd183e86f33a751aa438290036dc9ec101e934)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | git diff: Add --staged option | 2015-12-30T10:31:36 | [04eae51baf15](https://github.com/tldr-pages/tldr/commit/04eae51baf15d9adac52bfec6214fe51824061bf)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Update git-diff.md There was a type in `--name-only`. | 2015-04-14T16:30:02 | [6aa8fbc8aaae](https://github.com/tldr-pages/tldr/commit/6aa8fbc8aaae9705fa39b67396f5fdb017b21be0)
[Mateu Aguiló Bosch](mailto:mateu.aguilo.bosch@gmail.com) | Expand git-diff page Added: * `—names-only` option. * `—summary` option. | 2014-04-13T18:00:28 | [013116469ea6](https://github.com/tldr-pages/tldr/commit/013116469ea6926d3063c1c153be2d697a97b2a8)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

