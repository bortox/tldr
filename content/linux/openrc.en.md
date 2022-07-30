---
author: ['Starbeamrainbowlabs']
date: 1580130827
title: "openrc"
description: "openrc, The OpenRC service manager."
categories: "linux"
---
> See also `rc-status`, `rc-update`, and `rc-service`.

> More information: <https://wiki.gentoo.org/wiki/OpenRC>.

- Change to a specific runlevel:

```bash
sudo openrc runlevel_name
```

- Change to a specific runlevel, but don't stop any existing services:

```bash
sudo openrc --no-stop runlevel_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | openrc, rc-status, rc-service, rc-update: add pages (#3800) * rc-status: add page * openrc: add page * rc-service: add page * rc- [...] | 2020-01-27T14:13:47 | [a0d7c46e801a](https://github.com/tldr-pages/tldr/commit/a0d7c46e801a5d5874eae9a9ec55588863a97483)

