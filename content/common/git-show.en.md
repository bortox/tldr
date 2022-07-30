---
author: ['Waldir Pimenta', 'lucas schneider', 'alefir', 'CARE-COLIN Thibaut', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1610111394
title: "git show"
description: "git show, Show various types of Git objects (commits, tags, etc.)."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-show>.

- Show information about the latest commit (hash, message, changes, and other metadata):

```bash
git show
```

- Show information about a given commit:

```bash
git show commit
```

- Show information about the commit associated with a given tag:

```bash
git show tag
```

- Show information about the 3rd commit from the HEAD of a branch:

```bash
git show branch~3
```

- Show a commit's message in a single line, suppressing the diff output:

```bash
git show --oneline -s commit
```

- Show only statistics (added/removed characters) about the changed files:

```bash
git show --stat commit
```

- Show only the list of added, renamed or deleted files:

```bash
git show --summary commit
```

- Show the contents of a file as it was at a given revision (e.g. branch, tag or commit):

```bash
git show revision:path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-show: improve --stat, add --summary | 2020-10-28T19:37:32 | [c91bb1b19ce5](https://github.com/tldr-pages/tldr/commit/c91bb1b19ce519323d55d871a75405f234723791)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-show: add example for --stat option (#3728) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-01-03T00:19:40 | [29b3ab40a1a6](https://github.com/tldr-pages/tldr/commit/29b3ab40a1a63ac8b0e47c585990507abc6b7268)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-show: add example for showing file contents (#3600) | 2019-11-26T19:56:44 | [c5a8569ecede](https://github.com/tldr-pages/tldr/commit/c5a8569ecedef725ff61a23766f062a541b545e8)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-show: various tweaks (#1341) - adjust punctuation & spacing in main description - adjust descriptions ("changes" --> [...] | 2017-04-19T22:25:28 | [5cb62ebbffa4](https://github.com/tldr-pages/tldr/commit/5cb62ebbffa473bf9b53d230da8be138715dc19f)
[alefir](mailto:bob1nilly@gmail.com) | git-show: add page (#1331) | 2017-04-18T19:09:07 | [b71c9cdcf3fa](https://github.com/tldr-pages/tldr/commit/b71c9cdcf3faaf14c42dcbb839cc908625c0df88)

