---
author: ['Pierre Rudloff']
date: 1603541660
title: "gitlab-ctl, TLDR Pages"
description: "gitlab-ctl, CLI tool for managing the GitLab omnibus."
categories: "common"
---
> More information: <https://docs.gitlab.com/omnibus/maintenance/>.

- Display the status of every service:

```bash
sudo gitlab-ctl status
```

- Display the status of a specific service:

```bash
sudo gitlab-ctl status nginx
```

- Restart every service:

```bash
sudo gitlab-ctl restart
```

- Restart a specific service:

```bash
sudo gitlab-ctl restart nginx
```

- Display the logs of every service and keep reading until `Ctrl + C` is pressed:

```bash
sudo gitlab-ctl tail
```

- Display the logs of a specific service:

```bash
sudo gitlab-ctl tail nginx
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:50333926+prudloff-insite@users.noreply.github.com) | gitlab-ctl: add page (#4758) | 2020-10-24T14:14:20 | [c1c162faeebe](https://github.com/tldr-pages/tldr/commit/c1c162faeebe98c3f0d228c65c2c8ee3432cfce5)

