---
author: ['Waldir Pimenta', 'Sahil Dhiman']
date: 1609242414
title: "netselect, TLDR Pages"
description: "netselect, Speed test for choosing a fast network server."
categories: "linux"
---
> More information: <https://github.com/apenwarr/netselect>.

- Choose the server with the lowest latency:

```bash
sudo netselect host_1 host_2
```

- Display nameserver resolution and statistics:

```bash
sudo netselect -vv host_1 host_2
```

- Define maximum TTL (time to live):

```bash
sudo netselect -m 10 host_1 host_2
```

- Print fastest N servers among the hosts:

```bash
sudo netselect -s N host_1 host_2 host_3
```

- List available options:

```bash
netselect
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | netselect: add page (#4219) | 2020-08-10T00:59:53 | [ccd7f226eaca](https://github.com/tldr-pages/tldr/commit/ccd7f226eaca7531038195bca90984dec8fc783e)

