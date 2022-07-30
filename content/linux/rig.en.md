---
author: ['Axel Navarro', 'Neel Gopaul']
date: 1642131234
title: "rig"
description: "rig, Utility to piece together a random first name, last name, street number and address, along with a geographically consistent (ie, they all match the same area) city, state, ZIP code, and area code."
categories: "linux"
---
> More information: <https://manned.org/rig>.

- Display a random name (male or female) and address:

```bash
rig
```

- Display a [m]ale (or [f]emale) random name and address:

```bash
rig -m|f
```

- Use data files from a specific directory (default is `/usr/share/rig`):

```bash
rig -d path/to/directory
```

- Display a specific number of identities:

```bash
rig -c number
```

- Display a specific number of female identities:

```bash
rig -f -c number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)
[Neel Gopaul](mailto:neelmedhanshgopaul@gmail.com) | rig: add page (#4655) | 2020-10-14T12:01:17 | [b07f47238729](https://github.com/tldr-pages/tldr/commit/b07f4723872961471b9a3d1f921971872f0367e7)

