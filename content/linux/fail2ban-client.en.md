---
author: ['Antonio Bustos']
date: 1602010030
title: "fail2ban-client, TLDR Pages"
description: "fail2ban-client, Configure and control fail2ban server."
categories: "linux"
---
> More information: <https://github.com/fail2ban/fail2ban>.

- Retrieve current status of the jail service:

```bash
fail2ban-client status jail
```

- Remove the specified IP from the jail service's ban list:

```bash
fail2ban-client set jail unbanip ip
```

- Verify fail2ban server is alive:

```bash
fail2ban-client ping
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antonio Bustos](mailto:antoniobusrod@users.noreply.github.com) | fail2ban-client: add page (#4506) | 2020-10-06T20:47:10 | [1bd194c5346b](https://github.com/tldr-pages/tldr/commit/1bd194c5346baa010ffb6fc1ce1043a664f1512f)

