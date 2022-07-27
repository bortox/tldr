---
author: ['Waldir Pimenta', 'Wolfgang Lutz', 'Pradeep Reddy Raamana', 'Dario Vladović', 'Alfred Bez', 'muteness', 'marchersimon']
date: 1617292466
title: "uniq, TLDR Pages"
description: "uniq, Output the unique lines from the given input or file."
categories: "common"
---
> Since it does not detect repeated lines unless they are adjacent, we need to sort them first.

> More information: <https://www.gnu.org/software/coreutils/uniq>.

- Display each line once:

```bash
sort file | uniq
```

- Display only unique lines:

```bash
sort file | uniq -u
```

- Display only duplicate lines:

```bash
sort file | uniq -d
```

- Display number of occurrences of each line along with that line:

```bash
sort file | uniq -c
```

- Display number of occurrences of each line, sorted by the most frequent:

```bash
sort file | uniq -c | sort -nr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | uniq: add more information link (#5599) | 2021-03-30T15:47:39 | [496b40732442](https://github.com/tldr-pages/tldr/commit/496b407324427f69956303272d722738663c5c9a)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Alfred Bez](mailto:alfred.bez@googlemail.com) | sort uniq first (#954) 'uniq' does not detect repeated lines unless they are adjacent, so we need to sort them | 2016-07-15T13:18:37 | [8336898ea9d9](https://github.com/tldr-pages/tldr/commit/8336898ea9d97891bd81a0a3a0b7f71835814baf)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | uniq: add sorting example (#945) This involves another command, but it's such a natural extension of uniq's `-c` functionality that I [...] | 2016-07-10T11:26:13 | [fd5fb3562d47](https://github.com/tldr-pages/tldr/commit/fd5fb3562d475e63575b61de47e080fc0b99f164)
[Pradeep Reddy Raamana](mailto:raamana@gmail.com) | w: split out of common and add -i to osx, uniq: additions, seq: add page | 2016-01-23T18:03:00 | [525f436cc88c](https://github.com/tldr-pages/tldr/commit/525f436cc88c28ddf4d139d3314dc71b94ddcb24)
[muteness](mailto:chao0duan@gmail.com) | uniq: add page | 2016-01-13T19:23:56 | [f8cbd12e7027](https://github.com/tldr-pages/tldr/commit/f8cbd12e702716dbdec6c04503e4da4f11a90866)

