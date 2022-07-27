---
author: ['Azrael JD', 'Shashank Shekhar']
date: 1643125676
title: "swapoff, TLDR Pages"
description: "swapoff, Disables device or file for swapping."
categories: "linux"
---
> More information: <https://manned.org/swapoff>.

- Disable a given swap partition:

```bash
swapoff /dev/sdb7
```

- Disable a given swap file:

```bash
swapoff path/to/file
```

- Disable all swap areas:

```bash
swapoff -a
```

- Disable swap by label of a device or file:

```bash
swapoff -L swap1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | swapoff: add more information link (#7707) | 2022-01-25T16:47:56 | [64e0d783a9dc](https://github.com/tldr-pages/tldr/commit/64e0d783a9dc2c77af7ebd148fee63c0dd670e36)
[Shashank Shekhar](mailto:correspond.shashank@gmail.com) | swapoff: add page (#2003) | 2018-02-17T13:27:28 | [3d5fb28ceb48](https://github.com/tldr-pages/tldr/commit/3d5fb28ceb48e7d9f98e966612edf3b9e08c9dd1)

