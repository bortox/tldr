---
author: ['bl-ue', 'marchersimon']
date: 1621541621
title: "pio account, TLDR Pages"
description: "pio account, Manage your PlatformIO account in the command-line."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/account/>.

- Register a new PlatformIO account:

```bash
pio account register --username username --email email --password password --firstname firstname --lastname lastname
```

- Permanently delete your PlatformIO account and related data:

```bash
pio account destroy
```

- Log in to your PlatformIO account:

```bash
pio account login --username username --password password
```

- Log out of your PlatformIO account:

```bash
pio account logout
```

- Update your PlatformIO profile:

```bash
pio account update --username username --email email --firstname firstname --lastname lastname --current-password password
```

- Show detailed information about your PlatformIO account:

```bash
pio account show
```

- Reset your password using your username or email:

```bash
pio account forgot --username username_or_email
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-account: add page (#5410) | 2021-03-10T21:27:09 | [c2156e1b339b](https://github.com/tldr-pages/tldr/commit/c2156e1b339bac077fab0c025d2b6bce5eb87be3)

