---
author: ['Sahil Dhiman', 'Adam Herst']
date: 1615231512
title: "pvs"
description: "pvs, Display information about physical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/pvs.8.html>.

- Display information about physical volumes:

```bash
pvs
```

- Display non-physical volumes:

```bash
pvs -a
```

- Change default display to show more details:

```bash
pvs -v
```

- Display only specific fields:

```bash
pvs -o field_name_1,field_name_2
```

- Append field to default display:

```bash
pvs -o +field_name
```

- Suppress heading line:

```bash
pvs --noheadings
```

- Use separator to separate fields:

```bash
pvs --separator special_character
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | pvs: add information and man page (#4189) | 2020-07-16T23:26:45 | [f5bdb065e500](https://github.com/tldr-pages/tldr/commit/f5bdb065e500ed7a487affe8846f014dd394cf54)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | pvs: add page (#4156) | 2020-07-08T15:18:44 | [30ddeee0549f](https://github.com/tldr-pages/tldr/commit/30ddeee0549f607cb3f4a5886d56cabfab526ee8)

