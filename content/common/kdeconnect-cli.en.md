---
author: ['aaaawwWWWwwwwWWW', 'marchersimon']
date: 1624035825
title: "kdeconnect-cli"
description: "kdeconnect-cli, KDE Connect CLI."
categories: "common"
---
> More information: <https://kdeconnect.kde.org>.

- List all devices:

```bash
kdeconnect-cli --list-devices
```

- List available (paired and reachable) devices:

```bash
kdeconnect-cli --list-available
```

- Request pairing with a specific device, specifying its ID:

```bash
kdeconnect-cli --pair --device device_id
```

- Ring a device, specifying its name:

```bash
kdeconnect-cli --ring --name device_name
```

- Share an URL or file with a paired device, specifying its ID:

```bash
kdeconnect-cli --share URL|path/to/file --device device_id
```

- Send an SMS with an optional attachment to a specific number:

```bash
kdeconnect-cli --name device_name --send-sms message --destination phone_number --attachment path/to/file
```

- Unlock a specific device:

```bash
kdeconnect-cli --name device_name --unlock
```

- Simulate a key press on a specific device:

```bash
kdeconnect-cli --name device_name --send-keys key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[aaaawwWWWwwwwWWW](mailto:73749744+aaaawwWWWwwwwWWW@users.noreply.github.com) | kdeconnect-cli: add share file/url; remove redundant pair (#6119) | 2021-06-18T19:03:45 | [b63dc1abf0f4](https://github.com/tldr-pages/tldr/commit/b63dc1abf0f4735f053cea3c1e85a7d62275c9d8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | kdeconnect-cli: add page (#5866) | 2021-05-14T01:56:40 | [2391ffcc926c](https://github.com/tldr-pages/tldr/commit/2391ffcc926c048db6cdb7fc216515cdeea55c52)

