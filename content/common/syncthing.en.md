---
author: ['Shane Kimble', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "syncthing, TLDR Pages"
description: "syncthing, Continuous bidirectional decentralised folder synchronisation tool."
categories: "common"
---
> More information: <https://docs.syncthing.net/>.

- Start Syncthing:

```bash
syncthing
```

- Start Syncthing without opening a web browser:

```bash
syncthing -no-browser
```

- Print the device ID:

```bash
syncthing -device-id
```

- Change the home directory:

```bash
syncthing -home=path/to/directory
```

- Force a full index exchange:

```bash
syncthing -reset-deltas
```

- Change the address upon which the web interface listens:

```bash
syncthing -gui-address=ip_address:port|path/to/socket.sock
```

- Show filepaths to the files used by Syncthing:

```bash
syncthing -paths
```

- Disable the Syncthing monitor process:

```bash
syncthing -no-restart
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Shane Kimble](mailto:summonholmes@protonmail.com) | syncthing: add -no-browser example (#4700) | 2020-10-20T12:58:25 | [e8cbaab42411](https://github.com/tldr-pages/tldr/commit/e8cbaab42411d75c032ea2cb62899245b52a72ef)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | syncthing: add page (#4215) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-07-28T13:09:30 | [95ef1a04abf3](https://github.com/tldr-pages/tldr/commit/95ef1a04abf39be5f0dbeb29a842ed79509a5321)

