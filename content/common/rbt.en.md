---
author: ['Tyler Moon', 'bl-ue', 'Marco Bonelli']
date: 1621541621
title: "rbt"
description: "rbt, RBTools is a set of command-line tools for working with Review Board and RBCommons."
categories: "common"
---
> More information: <https://www.reviewboard.org/docs/rbtools/dev/>.

- Post changes to Review Board:

```bash
rbt post change_number
```

- Display the diff that will be sent to Review Board:

```bash
rbt diff
```

- Land a change in a local branch or on a review request:

```bash
rbt land branch_name
```

- Patch your tree with a change on a review request:

```bash
rbt patch review_request_id
```

- Set up RBTool to talk to a repository:

```bash
rbt setup-repo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Tyler Moon](mailto:moon.tyler@gmail.com) | rbt: add page (#2789) | 2019-02-20T04:58:28 | [2fa33cfe109a](https://github.com/tldr-pages/tldr/commit/2fa33cfe109a5052a500d9997f45c4bc9f26621e)

