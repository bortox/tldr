---
author: ['bl-ue', 'Thomas Museus Dabay']
date: 1621541621
title: "mocp"
description: "mocp, Music on Console (MOC) audio player."
categories: "linux"
---
> More information: <https://manned.org/mocp>.

- Launch the MOC terminal UI:

```bash
mocp
```

- Launch the MOC terminal UI in a specific directory:

```bash
mocp path/to/directory
```

- Start the MOC server in the background, without launching the MOC terminal UI:

```bash
mocp --server
```

- Add a specific song to the play queue while MOC is in the background:

```bash
mocp --enqueue path/to/audio_file
```

- Add songs recursively to the play queue while MOC is in the background:

```bash
mocp --append path/to/directory
```

- Clear the play queue while MOC is in the background:

```bash
mocp --clear
```

- Play or stop the currently queued song while MOC is in the background:

```bash
mocp --play|stop
```

- Stop the MOC server while it's in the background:

```bash
mocp --exit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bundle, mocp: fix typo (#5748) | 2021-04-14T16:12:42 | [d84f31d7db9e](https://github.com/tldr-pages/tldr/commit/d84f31d7db9e5f3131a822bcfc665e4af126d05c)
[Thomas Museus Dabay](mailto:41303137+thomas-m-d@users.noreply.github.com) | mocp: add page (#5734) | 2021-04-14T13:37:44 | [7755ac87fb16](https://github.com/tldr-pages/tldr/commit/7755ac87fb1672bb9dc50b8df7159c11e36ef9af)

