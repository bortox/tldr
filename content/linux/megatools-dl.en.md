---
author: ['newtant']
date: 1635204472
title: "megatools-dl"
description: "megatools-dl, Download files from `mega.nz`."
categories: "linux"
---
> Part of the `megatools` suite.

> More information: <https://megatools.megous.com/man/megatools-dl.html>.

- Download files from a `mega.nz` link into the current directory:

```bash
megatools-dl https://mega.nz/...
```

- Download files from a `mega.nz` link into a specific directory:

```bash
megatools-dl --path path/to/directory https://mega.nz/...
```

- Interactively choose which files to download:

```bash
megatools-dl --choose-files https://mega.nz/...
```

- Limit the download speed in KiB/s:

```bash
megatools-dl --limit-speed speed https://mega.nz/...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[newtant](mailto:newtant@users.noreply.github.com) | megadl: add page (#6600) | 2021-10-26T01:27:52 | [5ee7f8e16bc7](https://github.com/tldr-pages/tldr/commit/5ee7f8e16bc7d131f40eaffe01653e5272b89091)

