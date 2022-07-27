---
author: ['Emily']
date: 1655526350
title: "isisdl, TLDR Pages"
description: "isisdl, A downloading utility for ISIS of TU-Berlin. Download all your files and videos from ISIS."
categories: "common"
---
> More information: <https://github.com/Emily3403/isisdl>.

- Start the synchronization process:

```bash
isisdl
```

- Limit the download rate to 20 MiB/s and download with 5 threads:

```bash
isisdl --download-rate 20 --max-num-threads 5
```

- Run the initialization configuration wizard:

```bash
isisdl --init
```

- Run the additional configuration wizard:

```bash
isisdl --config
```

- Initiate a full synchronization of the database and compute the checksum of every file:

```bash
isisdl --sync
```

- Start ffmpeg to compress downloaded videos:

```bash
isisdl --compress
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily](mailto:90838511+Emily3403@users.noreply.github.com) | isisdl: add page (#8134) | 2022-06-18T06:25:50 | [95871dc69aa2](https://github.com/tldr-pages/tldr/commit/95871dc69aa2775c27a3a6733e77c9c2097d4f12)

