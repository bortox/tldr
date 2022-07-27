---
author: ['cyqsimon', 'Lucas Gabriel Schneider', 'Ein Verne']
date: 1642080520
title: "smbpasswd, TLDR Pages"
description: "smbpasswd, Add/remove a Samba user or change its password."
categories: "linux"
---
> Samba users must have an existing local Unix account.

> More information: <https://manned.org/smbpasswd.8>.

- Change the current user's SMB password:

```bash
smbpasswd
```

- Add a specified user to Samba and set password (user should already exist in system):

```bash
sudo smbpasswd -a username
```

- Modify an existing Samba user's password:

```bash
sudo smbpasswd username
```

- Delete a Samba user (use `pdbedit` instead if the Unix account has been deleted):

```bash
sudo smbpasswd -x username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cyqsimon](mailto:28627918+cyqsimon@users.noreply.github.com) | pdbedit, smbpassword: add page & improve comments (#7545) | 2022-01-13T14:28:40 | [34f822e7929f](https://github.com/tldr-pages/tldr/commit/34f822e7929f7b2c2284c725e94cc007fc76522f)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[Ein Verne](mailto:einverne@gmail.com) | smbpasswd: add page (#3382) | 2019-10-17T10:46:27 | [094242edc6f0](https://github.com/tldr-pages/tldr/commit/094242edc6f031da14e4c137cfd49b3c527db86e)

