---
author: ['Azrael JD', 'Ishaan Bhimwal', 'Starbeamrainbowlabs']
date: 1658240132
title: "rc-service, TLDR Pages"
description: "rc-service, Locate and run OpenRC services with arguments."
categories: "linux"
---
> See also `openrc`.

> More information: <https://manned.org/rc-service>.

- Show a service's status:

```bash
rc-service service_name status
```

- Start a service:

```bash
sudo rc-service service_name start
```

- Stop a service:

```bash
sudo rc-service service_name stop
```

- Restart a service:

```bash
sudo rc-service service_name restart
```

- Simulate running a service's custom command:

```bash
sudo rc-service --dry-run service_name command_name
```

- Actually run a service's custom command:

```bash
sudo rc-service service_name command_name
```

- Resolve the location of a service definition on disk:

```bash
sudo rc-service --resolve service_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | rc-service: add more information link (#7714) | 2022-01-27T15:23:46 | [aaada5f0e62e](https://github.com/tldr-pages/tldr/commit/aaada5f0e62e8f151b671f282bba53b0c77b227e)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | openrc, rc-status, rc-service, rc-update: add pages (#3800) * rc-status: add page * openrc: add page * rc-service: add page * rc- [...] | 2020-01-27T14:13:47 | [a0d7c46e801a](https://github.com/tldr-pages/tldr/commit/a0d7c46e801a5d5874eae9a9ec55588863a97483)

