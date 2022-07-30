---
author: ['Axel Navarro']
date: 1630935788
title: "pacman-key"
description: "pacman-key, Wrapper script for GnuPG used to manage pacman's keyring."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman-key>.

- Initialize the pacman keyring:

```bash
sudo pacman-key --init
```

- Add the default ArchLinux keys:

```bash
sudo pacman-key --populate archlinux
```

- List keys from the public keyring:

```bash
pacman-key --list-keys
```

- Add the specified keys:

```bash
sudo pacman-key --add path/to/keyfile.gpg
```

- Receive a key from a key server:

```bash
sudo pacman-key --recv-keys "uid|name|email"
```

- Print the fingerprint of a specific key:

```bash
pacman-key --finger "uid|name|email"
```

- Sign an imported key locally:

```bash
sudo pacman-key --lsign-key "uid|name|email"
```

- Remove a specific key:

```bash
sudo pacman-key --delete "uid|name|email"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-key: add page (#6474) | 2021-09-06T15:43:08 | [998e548ea5f6](https://github.com/tldr-pages/tldr/commit/998e548ea5f67871f5403fd7e6ca729cf27329dc)

