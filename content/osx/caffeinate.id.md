---
author: ['Theodorus Clarence']
date: 1633316741
title: "caffeinate"
description: "caffeinate, Menghindari macOS dari sleep (mode tidur)."
categories: "osx"
---
> Informasi lebih lanjut: <https://ss64.com/osx/caffeinate.html>.

- Menghindari mode sleep selama 1 jam (3600 detik):

```bash
caffeinate -u -t 3600
```

- Menghindari mode sleep sampai sebuah command selesai:

```bash
caffeinate -s command
```

- Menghindari mode sleep sampai anda mengetik Ctrl-C:

```bash
caffeinate -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Theodorus Clarence](mailto:55318172+theodorusclarence@users.noreply.github.com) | caffeinate: add Indonesian translation (#6668) | 2021-10-04T05:05:41 | [6c8eff66b726](https://github.com/tldr-pages/tldr/commit/6c8eff66b726b665408f527a41a70b9fc61edd94)

