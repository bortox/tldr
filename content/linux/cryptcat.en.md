---
author: ['ciph3rz']
date: 1636041073
title: "cryptcat, TLDR Pages"
description: "cryptcat, Cryptcat is netcat with encryption capabilities."
categories: "linux"
---
> More information: <http://cryptcat.sourceforge.net>.

- [l]isten on a specified [p]ort and print any data received:

```bash
cryptcat -k password -l -p port
```

- Connect to a certain port:

```bash
cryptcat -k password ip_address port
```

- Set a timeout [w]:

```bash
cryptcat -k password -w timeout_in_seconds ip_address port
```

- Scan [z] the open ports of a specified host:

```bash
cryptcat -v -z ip_address port
```

- Act as proxy and forward data from a local TCP port to the given remote host:

```bash
cryptcat -k password -l -p local_port | cryptcat -k password hostname remote_port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ciph3rz](mailto:46655414+ciph3rz@users.noreply.github.com) | cryptcat: add page (#7226) | 2021-11-04T16:51:13 | [86f9e45fc416](https://github.com/tldr-pages/tldr/commit/86f9e45fc416c3a9727392029b9aacc5c03dafa7)

