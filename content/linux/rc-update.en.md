---
author: ['Azrael JD', 'Starbeamrainbowlabs']
date: 1643286552
title: "rc-update, TLDR Pages"
description: "rc-update, Add and remove OpenRC services to and from runlevels."
categories: "linux"
---
> See also `openrc`.

> More information: <https://manned.org/rc-update>.

- List all services and the runlevels they are added to:

```bash
rc-update show
```

- Add a service to a runlevel:

```bash
sudo rc-update add service_name runlevel
```

- Delete a service from a runlevel:

```bash
sudo rc-update delete service_name runlevel
```

- Delete a service from all runlevels:

```bash
sudo rc-update --all delete service_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | rc-update: add more information link (#7716) | 2022-01-27T13:29:12 | [88f61f1d2e09](https://github.com/tldr-pages/tldr/commit/88f61f1d2e096b72a7410f8a2c6484c82a068e84)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | openrc, rc-status, rc-service, rc-update: add pages (#3800) * rc-status: add page * openrc: add page * rc-service: add page * rc- [...] | 2020-01-27T14:13:47 | [a0d7c46e801a](https://github.com/tldr-pages/tldr/commit/a0d7c46e801a5d5874eae9a9ec55588863a97483)

