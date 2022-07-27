---
author: ['Seth Falco', 'bl-ue']
date: 1629050349
title: "uuencode, TLDR Pages"
description: "uuencode, Encode binary files into ASCII for transport via mediums that only support simple ASCII encoding."
categories: "common"
---
> More information: <https://manned.org/uuencode>.

- Encode a file and print the result to stdout:

```bash
uuencode path/to/input_file output_file_name_after_decoding
```

- Encode a file and write the result to a file:

```bash
uuencode -o path/to/output_file path/to/input_file output_file_name_after_decoding
```

- Encode a file using Base64 instead of the default uuencode encoding and write the result to a file:

```bash
uuencode -m -o path/to/output_file path/to/input_file output_file_name_after_decoding
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | uuencode: add page (#5857) | 2021-05-01T20:28:28 | [883412726a44](https://github.com/tldr-pages/tldr/commit/883412726a44d767669fc225bb05f09ddcbcfa9d)

