---
author: ['Seth']
date: 1620676027
title: "mmcli"
description: "mmcli, Control and monitor the ModemManager."
categories: "linux"
---
> More information: <https://www.freedesktop.org/software/ModemManager/man/latest/mmcli.1.html>.

- List SMS messages available on the modem:

```bash
sudo mmcli --modem=modem --messaging-list-sms
```

- Delete a message from the modem, specifying its path:

```bash
sudo mmcli --modem=modem --messaging-delete-sms=path/to/message_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth](mailto:seth@falco.fun) | mmcli: add page (#5876) | 2021-05-10T21:47:07 | [b575ffe20703](https://github.com/tldr-pages/tldr/commit/b575ffe207039a4fafa0d6e406a182b9c0316505)

