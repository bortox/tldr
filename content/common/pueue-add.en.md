---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue add"
description: "pueue add, Enqueue a task for execution."
categories: "common"
---
> More information: <https://github.com/Nukesor/pueue>.

- Add any command to the default queue:

```bash
pueue add command
```

- Pass a list of flags or arguments to a command when enqueuing:

```bash
pueue add -- command --arg -f
```

- Add a command but do not start it if it's the first in a queue:

```bash
pueue add --stashed -- rsync --archive --compress /local/directory /remote/directory
```

- Add a command to a group and start it immediately, see `pueue group` to manage groups:

```bash
pueue add --immediate --group "CPU_intensive" -- ffmpeg -i input.mp4 frame_%d.png
```

- Add a command and start it after commands 9 and 12 finish successfully:

```bash
pueue add --after 9 12 --group "torrents" -- transmission-cli torrent_file.torrent
```

- Add a command with a label after some delay has passed, see `pueue enqueue` for valid datetime formats:

```bash
pueue add --label "compressing large file" --delay "wednesday 10:30pm" -- "7z a compressed_file.7z large_file.xml"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

