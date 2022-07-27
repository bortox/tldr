---
author: ['Alex', 'bl-ue']
date: 1610307737
title: "evil-winrm, TLDR Pages"
description: "evil-winrm, Windows Remote Management (WinRM) shell for pentesting."
categories: "common"
---
> Once connected, we get a PowerShell prompt on the target host.

> More information: <https://github.com/Hackplayers/evil-winrm>.

- Connect to a host:

```bash
evil-winrm --ip ip --user user --password password
```

- Connect to a host, passing the password hash:

```bash
evil-winrm --ip ip --user user --hash nt_hash
```

- Connect to a host, specifying directories for scripts and executables:

```bash
evil-winrm --ip ip --user user --password password --scripts path/to/scripts --executables path/to/executables
```

- Connect to a host, using SSL:

```bash
evil-winrm --ip ip --user user --password password --ssl --pub-key path/to/pubkey --priv-key path/to/privkey
```

- Upload a file to the host:

```bash
PS > upload path/to/local/file path/to/remote/file
```

- Get a list of loaded PowerShell functions:

```bash
PS > menu
```

- Load a PowerShell script from the `--scripts` directory:

```bash
PS > script.ps1
```

- Invoke a binary on the host from the `--executables` directory:

```bash
PS > Invoke-Binary binary.exe
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | evil-winrm: change folder to directory | 2021-01-10T20:42:17 | [b609a96b9ffe](https://github.com/tldr-pages/tldr/commit/b609a96b9ffe91ba7f251dd172a9653263b4181e)
[Alex](mailto:alexandre.dhondt@gmail.com) | evil-winrm: add page (#3956) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-04-06T12:59:55 | [0b4f5233af02](https://github.com/tldr-pages/tldr/commit/0b4f5233af021a4a67e92caac597224c296ee9cf)

