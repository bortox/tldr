---
author: ['CleanMachine1']
date: 1647032853
title: "mullvad"
description: "mullvad, CLI client for Mullvad VPN."
categories: "common"
---
> More information: <https://mullvad.net/>.

- Link your mullvad account with the specified account number:

```bash
mullvad account set account_number
```

- Enable LAN access while VPN is on:

```bash
mullvad lan set allow
```

- Establish the VPN tunnel:

```bash
mullvad connect
```

- Check status of VPN tunnel:

```bash
mullvad status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | mullvad: move to common (#7876) | 2022-03-11T22:07:33 | [25070ff4e792](https://github.com/tldr-pages/tldr/commit/25070ff4e792820ee5e6c9706d0b4f4f76392e13)

