---
author: ['Alexandre Hassan']
date: 1662058636
title: "gnmic set"
description: "gnmic set, Modify gnmi network device configuration."
categories: "common"
---
> More information: <https://gnmic.kmrd.dev/cmd/set>.

- Update the value of a path:

```bash
gnmic --address ip:port set --update-path path --update-value value
```

- Update the value of a path to match the contents of a json file:

```bash
gnmic -a ip:port set --update-path path --update-file filepath
```

- Replace the value of a path to match the contents of a json file:

```bash
gnmic -a ip:port set --replace-path path --replace-file filepath
```

- Delete the node at a given path:

```bash
gnmic -a ip:port set --delete path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexandre Hassan](mailto:alexhassan@live.ca) | gnmic: add page and subpages (#8367) * gnmic - add * Change file extension * Fix newlines * update gnmic pages and add gnmic sub alias [...] | 2022-09-01T20:57:16 | [ec300f80fa2d](https://github.com/tldr-pages/tldr/commit/ec300f80fa2d239ebf2a1b46afddc12468370506)

