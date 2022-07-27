---
author: ['Pierre Rudloff']
date: 1603541596
title: "gitlab-runner, TLDR Pages"
description: "gitlab-runner, CLI tool for managing GitLab runners."
categories: "common"
---
> More information: <https://docs.gitlab.com/runner/>.

- Register a runner:

```bash
sudo gitlab-runner register --url https://gitlab.example.com --registration-token token --name name
```

- Register a runner with a Docker executor:

```bash
sudo gitlab-runner register --url https://gitlab.example.com --registration-token token --name name --executor docker
```

- Unregister a runner:

```bash
sudo gitlab-runner unregister --name name
```

- Display the status of the runner service:

```bash
sudo gitlab-runner status
```

- Restart the runner service:

```bash
sudo gitlab-runner restart
```

- Check if the registered runners can connect to GitLab:

```bash
sudo gitlab-runner verify
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:50333926+prudloff-insite@users.noreply.github.com) | gitlab-runner: add page (#4759) | 2020-10-24T14:13:16 | [f20cd173384d](https://github.com/tldr-pages/tldr/commit/f20cd173384d8006b8113361222383bdd182e437)

