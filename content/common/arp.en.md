---
author: ['Nevada Sanchez', 'Guido Lena Cota', 'marchersimon']
date: 1618756407
title: "arp"
description: "arp, Show and manipulate your system's ARP cache."
categories: "common"
---
> More information: <https://manned.org/arp>.

- Show the current ARP table:

```bash
arp -a
```

- Clear the entire cache:

```bash
sudo arp -a -d
```

- Delete a specific entry:

```bash
arp -d address
```

- Create an entry in the ARP table:

```bash
arp -s address mac_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Nevada Sanchez](mailto:sanchez.nevada@gmail.com) | arp: Generalize to common and add cache clearing. | 2016-02-01T03:05:33 | [74d42d3e029b](https://github.com/tldr-pages/tldr/commit/74d42d3e029b7150e6fec1f1fd83e10067b30573)

