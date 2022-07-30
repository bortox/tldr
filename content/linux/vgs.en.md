---
author: ['Waldir Pimenta', 'Sahil Dhiman', 'Adam Herst']
date: 1615231512
title: "vgs"
description: "vgs, Display information about volume groups."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/vgs.8.html>.

- Display information about volume groups:

```bash
vgs
```

- Display all volume groups:

```bash
vgs -a
```

- Change default display to show more details:

```bash
vgs -v
```

- Display only specific fields:

```bash
vgs -o field_name_1,field_name_2
```

- Append field to default display:

```bash
vgs -o +field_name
```

- Suppress heading line:

```bash
vgs --noheadings
```

- Use separator to separate fields:

```bash
vgs --separator =
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | vgs: add page (#4164) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Starbeamrainbowlabs [...] | 2020-07-12T15:58:06 | [d7183c983de5](https://github.com/tldr-pages/tldr/commit/d7183c983de546614cf037f73d3f3f1eed823dc7)

