---
author: ['Ehab Alsharif', 'bl-ue', 'Guido Lena Cota']
date: 1621541621
title: "git ls-remote"
description: "git ls-remote, Git command for listing references in a remote repository based on name or URL."
categories: "common"
---
> If no name or URL are given, then the configured upstream branch will be used, or remote origin if the former is not configured.

> More information: <https://git-scm.com/docs/git-ls-remote>.

- Show all references in the default remote repository:

```bash
git ls-remote
```

- Show only heads references in the default remote repository:

```bash
git ls-remote --heads
```

- Show only tags references in the default remote repository:

```bash
git ls-remote --tags
```

- Show all references from a remote repository based on name or URL:

```bash
git ls-remote repository_url
```

- Show references from a remote repository filtered by a pattern:

```bash
git ls-remote repository_name "pattern"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-ls-remote: fix more information link | 2021-01-08T17:52:28 | [d4cf28316104](https://github.com/tldr-pages/tldr/commit/d4cf28316104bab7545110f1ca33e07f478fcf53)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Ehab Alsharif](mailto:36003641+sanehab@users.noreply.github.com) | git-ls-remote: add page (#4538) | 2020-10-08T13:50:01 | [8d27898ab6c7](https://github.com/tldr-pages/tldr/commit/8d27898ab6c75081484ba69354730b598e498b12)

