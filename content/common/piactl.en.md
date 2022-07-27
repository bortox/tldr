---
author: ['bl-ue', 'Owen Voke']
date: 1621541621
title: "piactl, TLDR Pages"
description: "piactl, The command-line tool for Private Internet Access, a commercial VPN provider."
categories: "common"
---
> More information: <https://privateinternetaccess.com/helpdesk/kb/articles/pia-desktop-command-line-interface>.

- Log in to Private Internet Access:

```bash
piactl login path/to/login_file
```

- Connect to Private Internet Access:

```bash
piactl connect
```

- Disconnect from Private Internet Access:

```bash
piactl disconnect
```

- Enable or disable the Private Internet Access daemon in the background:

```bash
piactl background enable|disable
```

- List all available VPN regions:

```bash
piactl get regions
```

- Display the current VPN region:

```bash
piactl get region
```

- Set your VPN region:

```bash
piactl set region region
```

- Log out of Private Internet Access:

```bash
piactl logout
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | piactl: add page (#4375) | 2020-10-02T21:09:01 | [05b2828bb461](https://github.com/tldr-pages/tldr/commit/05b2828bb4613fcb52b764ede0933b139835c54d)

