---
author: ['Wilco']
date: 1604660353
title: "amass track"
description: "amass track, Track differences between enumerations of the same domain."
categories: "common"
---
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-track-subcommand>.

- Show the difference between the last two enumerations of the specified domain:

```bash
amass track -dir path/to/database_directory -d domain_name -last 2
```

- Show the difference between a certain point in time and the last enumeration:

```bash
amass track -dir path/to/database_directory -d domain_name -since 01/02 15:04:05 2006 MST
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

