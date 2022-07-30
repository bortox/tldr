---
author: ['Axel Navarro', 'Patrice Denis', 'Sahil Dhiman']
date: 1641649180
title: "netselect-apt"
description: "netselect-apt, Create a `sources.list` file for a Debian mirror with the lowest latency."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/netselect-apt/netselect-apt.html>.

- Create `sources.list` using the lowest latency server:

```bash
sudo netselect-apt
```

- Specify Debian branch, stable is used by default:

```bash
sudo netselect-apt testing
```

- Include non-free section:

```bash
sudo netselect-apt --non-free
```

- Specify a country for the mirror list lookup:

```bash
sudo netselect-apt -c India
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | netselect-apt: add page (#4262) | 2020-08-19T13:47:06 | [0a00c5326aa9](https://github.com/tldr-pages/tldr/commit/0a00c5326aa9add9d46f9d53c28944057d66beb7)

