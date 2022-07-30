---
author: ['Owen Voke', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'bl-ue', 'Seth Falco']
date: 1629050349
title: "webtorrent"
description: "webtorrent, The command-line interface for WebTorrent."
categories: "common"
---
> Supports magnets, URLs, info hashes and `.torrent` files.

> More information: <https://github.com/webtorrent/webtorrent-cli>.

- Download a torrent:

```bash
webtorrent download "torrent_id"
```

- Stream a torrent to VLC media player:

```bash
webtorrent download "torrent_id" --vlc
```

- Stream a torrent to a Digital Living Network Alliance (DLNA) device:

```bash
webtorrent download "torrent_id" --dlna
```

- Display a list of files for a specific torrent:

```bash
webtorrent download "torrent_id" --select
```

- Specify a file index from the torrent to download:

```bash
webtorrent download "torrent_id" --select index
```

- Seed a specific file or directory:

```bash
webtorrent seed path/to/file_or_directory
```

- Create a new torrent file for the specified file path:

```bash
webtorrent create path/to/file
```

- Display information for a magnet URI or `.torrent` file:

```bash
webtorrent info path/to/file_or_magnet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Owen Voke](mailto:owzie123@gmail.com) | webtorrent: add page (#2659) | 2018-12-22T12:57:41 | [761c2dc7187e](https://github.com/tldr-pages/tldr/commit/761c2dc7187ee95b3b0dde1ff1d974ce9456116e)

