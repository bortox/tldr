---
author: ['dgcampea']
date: 1628545966
title: "xdelta, TLDR Pages"
description: "xdelta, Delta encoding utility."
categories: "common"
---
> Often used for applying patches to binary files.

> More information: <http://xdelta.org>.

- Apply a patch:

```bash
xdelta -d -s path/to/input_file path/to/delta_file.xdelta path/to/output_file
```

- Create a patch:

```bash
xdelta -e -s path/to/old_file path/to/new_file path/to/output_file.xdelta
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dgcampea](mailto:59268455+dgcampea@users.noreply.github.com) | xdelta: add page (#6313) | 2021-08-09T23:52:46 | [444b2ef58cf4](https://github.com/tldr-pages/tldr/commit/444b2ef58cf425c34ee9f6845c09fe38d8e3ba1e)

