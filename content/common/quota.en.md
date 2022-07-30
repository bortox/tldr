---
author: ['Waldir Pimenta', 'kalebo', 'Joshua Shanks', 'Starbeamrainbowlabs', 'Seth Falco']
date: 1633557112
title: "quota"
description: "quota, Display users' disk space usage and allocated limits."
categories: "common"
---
> More information: <https://manned.org/quota>.

- Show disk quotas in human-readable units for the current user:

```bash
quota -s
```

- Verbose output (also display quotas on filesystems where no storage is allocated):

```bash
quota -v
```

- Quiet output (only display quotas on filesystems where usage is over quota):

```bash
quota -q
```

- Print quotas for the groups of which the current user is a member:

```bash
quota -g
```

- Show disk quotas for another user:

```bash
sudo quota -u username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | ps, pv, pygmentize, quota, rabin2: add link (#6830) | 2021-10-06T23:51:52 | [52b9aaf74c57](https://github.com/tldr-pages/tldr/commit/52b9aaf74c571d0ee04b6f2986e09fff22ba7256)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update quota.md | 2017-05-24T10:32:16 | [497a561ae126](https://github.com/tldr-pages/tldr/commit/497a561ae126239ce0047c8c76e82a8cff1f302a)
[kalebo](mailto:kaleb.olson@gmail.com) | Tweaked quota example | 2017-05-24T10:32:16 | [d0ebfa44a59d](https://github.com/tldr-pages/tldr/commit/d0ebfa44a59de16800767e57a72a3623a184438c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix format | 2016-06-25T10:44:23 | [747259fd62fb](https://github.com/tldr-pages/tldr/commit/747259fd62fb6e081921a0f7bc6ec1eb9a3df988)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix format | 2016-06-25T10:42:42 | [b38c300b9126](https://github.com/tldr-pages/tldr/commit/b38c300b91266ea8c7b5e702c0617779f2e44b89)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add quota.md (fixes #832) | 2016-06-25T02:17:37 | [49771b150ed8](https://github.com/tldr-pages/tldr/commit/49771b150ed823988a36b5a965c7d1ff8e5ed088)

