---
author: ['Polle Vanhoof', 'zlbabe', 'Emily Grace Seville']
date: 1647882468
title: "ncat, TLDR Pages"
description: "ncat, Use the normal `cat` functionality over networks."
categories: "linux"
---
> More information: <https://manned.org/ncat>.

- Listen for input on the specified port and write it to the specified file:

```bash
ncat -l port > path/to/file
```

- Accept multiple connections and keep ncat open after they have been closed:

```bash
ncat -lk port
```

- Write output of specified file to the specified host on the specified port:

```bash
ncat address port < path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | ncat: add -k option (#2043) | 2018-03-26T09:47:48 | [c610a12f8442](https://github.com/tldr-pages/tldr/commit/c610a12f8442271fd620e912308ab6652bcd0c6d)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | ncat: update description and style | 2017-11-06T12:00:45 | [4ce03d950c9c](https://github.com/tldr-pages/tldr/commit/4ce03d950c9cdadcbe6d2158194a020587a7f523)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | ncat: add missing dots | 2017-11-01T22:48:18 | [9b6606587bf5](https://github.com/tldr-pages/tldr/commit/9b6606587bf5c9ee3bf522d9e80c270216f7a3eb)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | ncat ncat: create page | 2017-11-01T20:52:54 | [f7b7265c3e9d](https://github.com/tldr-pages/tldr/commit/f7b7265c3e9dca6a719b7ec4b14dfc1ea13a3170)

