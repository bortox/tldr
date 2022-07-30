---
author: ['bl-ue', 'Matthew Peveler', 'marchersimon']
date: 1621541621
title: "finger"
description: "finger, User information lookup program."
categories: "common"
---
> More information: <https://manned.org/finger>.

- Display information about currently logged in users:

```bash
finger
```

- Display information about a specific user:

```bash
finger username
```

- Display the user's login name, real name, terminal name, and other information:

```bash
finger -s
```

- Produce multiline output format displaying same information as `-s` as well as user's home directory, home phone number, login shell, mail status, etc.:

```bash
finger -l
```

- Prevent matching against user's names and only use login names:

```bash
finger -m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | finger: add page (#2141) | 2018-06-19T18:10:44 | [4cf731ce1d7c](https://github.com/tldr-pages/tldr/commit/4cf731ce1d7c3be439d926edf8215b4c51c9255d)

