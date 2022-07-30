---
author: ['Owen Voke', 'Marco Bonelli']
date: 1560687160
title: "deluge-console"
description: "deluge-console, An interactive interface for the Deluge BitTorrent client."
categories: "common"
---
> More information: <https://deluge-torrent.org>.

- Start the interactive console interface:

```bash
deluge-console
```

- Connect to a Deluge daemon instance:

```bash
connect hostname:port
```

- Add a torrent to the daemon:

```bash
add url|magnet|path/to/file
```

- Display information about all torrents:

```bash
info
```

- Display information about a specific torrent:

```bash
info torrent_id
```

- Pause a torrent:

```bash
pause torrent_id
```

- Resume a torrent:

```bash
resume torrent_id
```

- Remove a torrent from the daemon:

```bash
rm torrent_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | deluged, deluge-console: clarify description (#3109) | 2019-06-16T14:12:40 | [05b74bd91a9a](https://github.com/tldr-pages/tldr/commit/05b74bd91a9a181ea151dfee5611581812431639)
[Owen Voke](mailto:owzie123@gmail.com) | deluge-console: add page (#3058) | 2019-05-29T15:12:45 | [9d3f8109d7ce](https://github.com/tldr-pages/tldr/commit/9d3f8109d7cee96b8d92ceb759f7064086816b25)

