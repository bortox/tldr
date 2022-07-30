---
author: ['Ein Verne', 'marchersimon']
date: 1618584134
title: "transmission-create"
description: "transmission-create, A CLI utility to create BitTorrent .torrent files."
categories: "common"
---
> More information: <https://manned.org/transmission-create>.

- Create a torrent with 2048 KB as the piece size:

```bash
transmission-create -o path/to/example.torrent --tracker tracker_announce_url --piecesize 2048 path/to/file_or_directory
```

- Create a private torrent with a 2048 KB piece size:

```bash
transmission-create -p -o path/to/example.torrent --tracker tracker_announce_url --piecesize 2048 path/to/file_or_directory
```

- Create a torrent with a comment:

```bash
transmission-create -o path/to/example.torrent --tracker tracker_url1 -c comment path/to/file_or_directory
```

- Create a torrent with multiple trackers:

```bash
transmission-create -o path/to/example.torrent --tracker tracker_url1 --tracker tracker_url2 path/to/file_or_directory
```

- Show help page:

```bash
transmission-create --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Ein Verne](mailto:einverne@gmail.com) | transmission-create: add page (#3916) | 2020-03-23T06:50:19 | [d8ab1cfe97a7](https://github.com/tldr-pages/tldr/commit/d8ab1cfe97a75b38e9d4be1bc5f0e43e96e0d85a)

