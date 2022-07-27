---
author: ['xxchan']
date: 1647715136
title: "comby, TLDR Pages"
description: "comby, Tool for structural code search and replace that supports many languages."
categories: "common"
---
> More information: <https://github.com/comby-tools/comby>.

- Match and rewrite templates, and print changes:

```bash
comby 'assert_eq!(:[a], :[b])' 'assert_eq!(:[b], :[a])' .rs
```

- Match and rewrite with rewrite properties:

```bash
comby 'assert_eq!(:[a], :[b])' 'assert_eq!(:[b].Capitalize, :[a])' .rs
```

- Match and rewrite in-place:

```bash
comby -in-place 'match_pattern' 'rewrite_pattern'
```

- Only perform matching and print matches:

```bash
comby -match-only 'match_pattern' ""
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[xxchan](mailto:37948597+xxchan@users.noreply.github.com) | comby: add page (#7847) | 2022-03-19T19:38:56 | [97e49ad1d437](https://github.com/tldr-pages/tldr/commit/97e49ad1d437ffbea872a00e14353f2f425b8dac)

