---
author: ['Guido Lena Cota', 'Alison Li']
date: 1604238005
title: "git send-email"
description: "git send-email, Send a collection of patches as emails."
categories: "common"
---
> Patches can be specified as files, directions, or a revision list.

> More information: <https://git-scm.com/docs/git-send-email>.

- Send the last commit in the current branch:

```bash
git send-email -1
```

- Send a given commit:

```bash
git send-email -1 commit
```

- Send multiple (e.g. 10) commits in the current branch:

```bash
git send-email -10
```

- Send an introductory email message for the patch series:

```bash
git send-email -number_of_commits --compose
```

- Review and edit the email message for each patch you're about to send:

```bash
git send-email -number_of_commits --annotate
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Alison Li](mailto:alison.li2@mail.mcgill.ca) | git-send-email: improve examples and descriptions (#3953) | 2020-09-09T02:29:48 | [9c7e50848db4](https://github.com/tldr-pages/tldr/commit/9c7e50848db4da4be6683ace52526923c7a3f86d)
[Alison Li](mailto:alison.li2@mail.mcgill.ca) | git-send-email: fix syntax (#3953) | 2020-09-09T02:29:48 | [0df0e02d485f](https://github.com/tldr-pages/tldr/commit/0df0e02d485f67213d454616d45ecb1b19ac185e)
[Alison Li](mailto:alison.li2@mail.mcgill.ca) | git-send-email: add page (#3953) | 2020-09-09T02:29:48 | [2c4a92d23477](https://github.com/tldr-pages/tldr/commit/2c4a92d234778bf35642920aa0beff186ac151bb)

