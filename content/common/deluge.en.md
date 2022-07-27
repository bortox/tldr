---
author: ['bl-ue', 'Owen Voke']
date: 1621541621
title: "deluge, TLDR Pages"
description: "deluge, A command-line BitTorrent client."
categories: "common"
---
> More information: <https://deluge-torrent.org>.

- Download a torrent:

```bash
deluge url|magnet|path/to/file
```

- Download a torrent using a specific configuration file:

```bash
deluge -c path/to/configuration_file url|magnet|path/to/file
```

- Download a torrent and launch the specified user interface:

```bash
deluge -u gtk|web|console url|magnet|path/to/file
```

- Download a torrent and output the log to a file:

```bash
deluge -l path/to/log_file url|magnet|path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:owzie123@gmail.com) | deluge: add page (#3101) | 2019-06-10T15:12:07 | [f0d8b51caf6c](https://github.com/tldr-pages/tldr/commit/f0d8b51caf6c706a19a321b13562d71a169ee839)

