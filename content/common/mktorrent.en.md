---
author: ['Ein Verne']
date: 1584879105
title: "mktorrent, TLDR Pages"
description: "mktorrent, A CLI utility to create BitTorrent metainfo files."
categories: "common"
---
> More information: <https://github.com/Rudde/mktorrent>.

- Create a torrent with 2^21 KB as the piece size:

```bash
mktorrent -a tracker_announce_url -l 21 -o path/to/example.torrent path/to/file_or_directory
```

- Create a private torrent with a 2^21 KB piece size:

```bash
mktorrent -p -a tracker_announce_url -l 21 -o path/to/example.torrent path/to/file_or_directory
```

- Create a torrent with a comment:

```bash
mktorrent -c "comment" -a tracker_announce_url -l 21 -o path/to/example.torrent path/to/file_or_directory
```

- Create a torrent with multiple trackers:

```bash
mktorrent -a tracker_announce_url,tracker_announce_url_2 -l 21 -o path/to/example.torrent path/to/file_or_directory
```

- Create a torrent with web seed URLs:

```bash
mktorrent -a tracker_announce_url -w web_seed_url -l 21 -o path/to/example.torrent path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | mktorrent: add page (#3923) | 2020-03-22T13:11:45 | [a041034a9817](https://github.com/tldr-pages/tldr/commit/a041034a9817d64088a9084464b7996cd938a3b9)

