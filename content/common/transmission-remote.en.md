---
author: ['Alexander', 'pxgamer', 'Guido Lena Cota', 'Marco Bonelli', 'Managor', 'bl-ue']
date: 1615467423
title: "transmission-remote"
description: "transmission-remote, Remote control utility for transmission-daemon and transmission."
categories: "common"
---
> More information: <https://transmissionbt.com>.

- Add a torrent file or magnet link to Transmission and download to a specified directory:

```bash
transmission-remote hostname -a torrent|url -w /path/to/download_directory
```

- Change the default download directory:

```bash
transmission-remote hostname -w /path/to/download_directory
```

- List all torrents:

```bash
transmission-remote hostname --list
```

- Start torrent 1 and 2, stop torrent 3:

```bash
transmission-remote hostname -t "1,2" --start -t 3 --stop
```

- Remove torrent 1 and 2, and also delete local data for torrent 2:

```bash
transmission-remote hostname -t 1 --remove -t 2 --remove-and-delete
```

- Stop all torrents:

```bash
transmission-remote hostname -t all --stop
```

- Move torrents 1-10 and 15-20 to a new directory (which will be created if it does not exist):

```bash
transmission-remote hostname -t "1-10,15-20" --move /path/to/new_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | transmission-remote: fix to absolute paths (#5412) | 2021-03-11T13:57:03 | [585e1415c991](https://github.com/tldr-pages/tldr/commit/585e1415c9914457a6fabcee322659845dbd7288)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | transmission-remote: change folder to directory | 2021-01-10T20:42:17 | [7582d93776dc](https://github.com/tldr-pages/tldr/commit/7582d93776dc15b9079217876b7849bcdd6c2c2d)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | transmission-remote: add link to homepage | 2019-05-14T19:58:59 | [f7c41b8f72ba](https://github.com/tldr-pages/tldr/commit/f7c41b8f72baad2d1a407453d5941805622c322a)
[Alexander](mailto:2683344+terminalnode@users.noreply.github.com) | transmission-remote: add page (#2982) | 2019-05-09T18:37:39 | [8a5ab266a234](https://github.com/tldr-pages/tldr/commit/8a5ab266a2348279b0f8a080255135a3d314103b)

