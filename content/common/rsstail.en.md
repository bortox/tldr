---
author: ['pxgamer', 'melgu', 'bl-ue']
date: 1621541621
title: "rsstail, TLDR Pages"
description: "rsstail, `tail` for RSS feeds."
categories: "common"
---
> More information: <https://github.com/gvalkov/rsstail.py>.

- Show the feed of a given URL and wait for new entries appearing at the bottom:

```bash
rsstail -u url
```

- Show the feed in reverse chronological order (newer at the bottom):

```bash
rsstail -r -u url
```

- Include publication date and link:

```bash
rsstail -pl -u url
```

- Set update interval:

```bash
rsstail -u url -i interval_in_seconds
```

- Show feed and exit:

```bash
rsstail -1 -u url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rsstail: add link to homepage | 2019-05-29T14:41:10 | [9d044773ff25](https://github.com/tldr-pages/tldr/commit/9d044773ff25f2f6c7cad9ee443d6cb70b129842)
[melgu](mailto:mail@melvin-gundlach.de) | rsstail: add page (#2249) | 2018-08-23T05:57:01 | [6a46703a0193](https://github.com/tldr-pages/tldr/commit/6a46703a019309ab5657647300cd2411c593f253)

