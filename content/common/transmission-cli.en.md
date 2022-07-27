---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "transmission-cli, TLDR Pages"
description: "transmission-cli, A lightweight, command-line BitTorrent client."
categories: "common"
---
> This tool has been deprecated, please see `transmission-remote`.

> More information: <https://transmissionbt.com>.

- Download a specific torrent:

```bash
transmission-cli url|magnet|path/to/file
```

- Download a torrent to a specific directory:

```bash
transmission-cli --download-dir path/to/download_directory url|magnet|path/to/file
```

- Create a torrent file from a specific file or directory:

```bash
transmission-cli --new path/to/source_file_or_directory
```

- Set the download speed limit to 50 KB/s:

```bash
transmission-cli --downlimit 50 url|magnet|path/to/file
```

- Set the upload speed limit to 50 KB/s:

```bash
transmission-cli --uplimit 50 url|magnet|path/to/file
```

- Use a specific port for connections:

```bash
transmission-cli --port port_number url|magnet|path/to/file
```

- Force encryption for peer connections:

```bash
transmission-cli --encryption-required url|magnet|path/to/file
```

- Use a Bluetack-formatted peer blocklist:

```bash
transmission-cli --blocklist blocklist_url|path/to/blocklist url|magnet|path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | transmission-cli: add deprecation message (#2998) | 2019-05-09T18:39:08 | [2a75cabc2638](https://github.com/tldr-pages/tldr/commit/2a75cabc263861b12cbcf57fbc90ed8f8f88f630)
[pxgamer](mailto:owzie123@gmail.com) | transmission-cli: add page | 2019-05-04T20:01:54 | [9fc12f5973e7](https://github.com/tldr-pages/tldr/commit/9fc12f5973e7718948fee50b1f1ca6e94ead4565)

