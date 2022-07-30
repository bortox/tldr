---
author: ['Ilya Pantsyr']
date: 1650787217
title: "wondershaper"
description: "wondershaper, Allows the user to limit the bandwidth of one or more network adapters."
categories: "common"
---
> More information: <https://github.com/magnific0/wondershaper#usage>.

- Display [h]elp:

```bash
wondershaper -h
```

- Show the current [s]tatus of a specific [a]dapter:

```bash
wondershaper -s -a adapter_name
```

- Clear limits from a specific [a]dapter:

```bash
wondershaper -c -a adapter_name
```

- Set a specific maximum [d]ownload rate (in Kbps):

```bash
wondershaper -a adapter_name -d 1024
```

- Set a specific maximum [u]pload rate (in Kbps):

```bash
wondershaper -a adapter_name -u 512
```

- Set a specific maximum [d]ownload rate and [u]pload rate (in Kpbs):

```bash
wondershaper -a adapter_name -d 1024 -u 512
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | wondershaper: add page (#8034) | 2022-04-24T10:00:17 | [3ed1a673c079](https://github.com/tldr-pages/tldr/commit/3ed1a673c0794b3b8bbe1d5382171b84c692eb86)

