---
author: ['Owen Voke']
date: 1590024499
title: "AdGuardHome, TLDR Pages"
description: "AdGuardHome, A network-wide software for blocking ads & tracking."
categories: "common"
---
> More information: <https://github.com/AdguardTeam/AdGuardHome>.

- Run AdGuard Home:

```bash
AdGuardHome
```

- Run AdGuard Home with a specific config:

```bash
AdGuardHome --config path/to/AdGuardHome.yaml
```

- Set the work directory for data to be stored in:

```bash
AdGuardHome --work-dir path/to/directory
```

- Install or uninstall AdGuard Home as a service:

```bash
AdGuardHome --service install|uninstall
```

- Start the AdGuard Home service:

```bash
AdGuardHome --service start
```

- Reload the configuration for the AdGuard Home service:

```bash
AdGuardHome --service reload
```

- Stop or restart the AdGuard Home service:

```bash
AdGuardHome --service stop|restart
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | adguardhome: add page (#4055) | 2020-05-21T03:28:19 | [339fde77d61c](https://github.com/tldr-pages/tldr/commit/339fde77d61c1374fd5ef68b0958393c34bd363a)

