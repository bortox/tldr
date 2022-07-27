---
author: ['Stig124', 'Ben Glanton', 'Ray Voice']
date: 1625841955
title: "ac, TLDR Pages"
description: "ac, Print statistics on how long users have been connected."
categories: "linux"
---
> More information: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Print how long the current user has been connected in hours:

```bash
ac
```

- Print how long users have been connected in hours:

```bash
ac --individual-totals
```

- Print how long a particular user has been connected in hours:

```bash
ac --individual-totals username
```

- Print how long a particular user has been connected in hours per day (with total):

```bash
ac --daily-totals --individual-totals username
```

- Also display additional details:

```bash
ac --compatibility
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | ac: add --compatibility example (#4523) | 2020-10-14T23:58:31 | [78c84c8e60d4](https://github.com/tldr-pages/tldr/commit/78c84c8e60d483b152674920d0549ed879e5b97d)
[Ben Glanton](mailto:56129020+glantonb@users.noreply.github.com) | ac: add page (#3316) | 2019-10-06T11:51:05 | [8e8982246709](https://github.com/tldr-pages/tldr/commit/8e89822467092d63f7c7bf496c6c9dce2d75b219)

