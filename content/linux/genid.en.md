---
author: ['Blake L']
date: 1620733649
title: "genid"
description: "genid, Generate IDs, such as snowflakes, UUIDs, and a new GAID."
categories: "linux"
---
> More information: <https://github.com/bleonard252/genid>.

- Generate a UUIDv4:

```bash
genid uuid
```

- Generate a UUIDv5 using a namespace UUID and a specific name:

```bash
genid uuidv5 {ce598faa-8dd0-49ee-8525-9e24fff71dca} name
```

- Generate a Discord Snowflake, without a trailing newline (useful in shell scripts):

```bash
genid --script snowflake
```

- Generate a Generic Anonymous ID with a specific "real ID":

```bash
genid gaid real_id
```

- Generate a Snowflake with the epoch set to a specific date:

```bash
genid snowflake --epoch=unix_epoch_time
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Blake L](mailto:bleonard252@rocketmail.com) | genid: add page (#5867) | 2021-05-11T13:47:29 | [c92b8f10f3d6](https://github.com/tldr-pages/tldr/commit/c92b8f10f3d6f5ba4a0c0190aa46c0bebb3a43b7)

