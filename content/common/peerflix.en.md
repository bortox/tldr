---
author: ['Waldir Pimenta', 'David Aerne', 'pxgamer']
date: 1559328460
title: "peerflix, TLDR Pages"
description: "peerflix, Stream video- or audio-based torrents to a media player."
categories: "common"
---
> More information: <https://github.com/mafintosh/peerflix>.

- Stream the largest media file in a torrent:

```bash
peerflix "torrent_url|magnet_link"
```

- List all streamable files contained in a torrent (given as a magnet link):

```bash
peerflix "magnet:?xt=urn:btih:0123456789abcdef0123456789abcdef01234567" --list
```

- Stream the largest file in a torrent, given as a torrent URL, to VLC:

```bash
peerflix "http://example.net/music.torrent" --vlc
```

- Stream the largest file in a torrent to MPlayer, with subtitles:

```bash
peerflix "torrent_url|magnet_link" --mplayer --subtitles subtitle-file.srt
```

- Stream all files from a torrent to Airplay:

```bash
peerflix "torrent_url|magnet_link" --all --airplay
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | peerflix: add link to homepage | 2019-05-31T20:47:40 | [4343de550df4](https://github.com/tldr-pages/tldr/commit/4343de550df410a359555afb7d4c7f807929d3e8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | peerflix: move listing command further up | 2017-09-27T13:21:45 | [bd284f03f17a](https://github.com/tldr-pages/tldr/commit/bd284f03f17a9f5d942f9db74f8d54fc40e60e97)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | peerflix: expand based on official docs - add a torrent url example - add the --list and --subtitles options - make the magnet link [...] | 2017-09-01T11:09:33 | [802eb6c5af19](https://github.com/tldr-pages/tldr/commit/802eb6c5af194f6f1ada5cfb176689b73bdd5fb0)
[David Aerne](mailto:meodai@gmail.com) | peerflix: adds page (#1457) | 2017-08-31T21:13:56 | [d9136fd5643b](https://github.com/tldr-pages/tldr/commit/d9136fd5643b85bc7bf7045f0b132b35b1c42379)

