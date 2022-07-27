---
author: ['bl-ue', 'Starbeamrainbowlabs']
date: 1621541621
title: "git show-branch, TLDR Pages"
description: "git show-branch, Show branches and their commits."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-show-branch>.

- Show a summary of the latest commit on a branch:

```bash
git show-branch branch_name|ref|commit
```

- Compare commits in the history of multiple commits or branches:

```bash
git show-branch branch_name|ref|commit
```

- Compare all remote tracking branches:

```bash
git show-branch --remotes
```

- Compare both local and remote tracking branches:

```bash
git show-branch --all
```

- List the latest commits in all branches:

```bash
git show-branch --all --list
```

- Compare a given branch with the current branch:

```bash
git show-branch --current commit|branch_name|ref
```

- Display the commit name instead of the relative name:

```bash
git show-branch --sha1-name --current current|branch_name|ref
```

- Keep going a given number of commits past the common ancestor:

```bash
git show-branch --more 5 commit|branch_name|ref commit|branch_name|ref ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-show-branch: add page (#4016) | 2020-05-10T15:51:01 | [262994c9da91](https://github.com/tldr-pages/tldr/commit/262994c9da9159cf971504e7a1855191c7c2f9bf)

