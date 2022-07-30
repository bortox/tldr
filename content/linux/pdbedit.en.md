---
author: ['cyqsimon']
date: 1642080520
title: "pdbedit"
description: "pdbedit, Edit the Samba user database."
categories: "linux"
---
> For simple user add/remove/password, you can also use `smbpasswd`.

> More information: <https://manned.org/pdbedit>.

- List all Samba users (use verbose flag to show their settings):

```bash
sudo pdbedit --list --verbose
```

- Add an existing Unix user to Samba (will prompt for password):

```bash
sudo pdbedit --user username --create
```

- Remove a Samba user:

```bash
sudo pdbedit --user username --delete
```

- Reset a Samba user's failed password counter:

```bash
sudo pdbedit --user username --bad-password-count-reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cyqsimon](mailto:28627918+cyqsimon@users.noreply.github.com) | pdbedit, smbpassword: add page & improve comments (#7545) | 2022-01-13T14:28:40 | [34f822e7929f](https://github.com/tldr-pages/tldr/commit/34f822e7929f7b2c2284c725e94cc007fc76522f)

