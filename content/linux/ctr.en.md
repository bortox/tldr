---
author: ['hellojukay', 'Ishaan Bhimwal', 'bl-ue']
date: 1658240132
title: "ctr, TLDR Pages"
description: "ctr, Manage `containerd` containers and images."
categories: "linux"
---
> More information: <https://containerd.io>.

- List all containers (running and stopped):

```bash
ctr containers list
```

- List all images:

```bash
ctr images list
```

- Pull an image:

```bash
ctr images pull image
```

- Tag an image:

```bash
ctr images tag source_image:source_tag target_image:target_tag
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[hellojukay](mailto:licong@qianxin.com) | ctr: add page (#4928) | 2020-11-05T11:09:18 | [ca9301add6d5](https://github.com/tldr-pages/tldr/commit/ca9301add6d5ff8f1cff964ecd91fec298d0395b)

