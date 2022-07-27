---
author: ['Furkan']
date: 1634756728
title: "in-toto-record, TLDR Pages"
description: "in-toto-record, Create a signed link metadata file to provide evidence for supply chain steps."
categories: "common"
---
> More information: <https://in-toto.readthedocs.io/en/latest/command-line-tools/in-toto-record.html>.

- Start the record (creates a preliminary link file):

```bash
in-toto-record start -n edit-files -k path/to/key_file -m .
```

- Stop the record (expects a preliminary link file):

```bash
in-toto-record stop -n edit-files -k path/to/key_file -p .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | in-toto-record: add page | 2021-10-20T21:05:28 | [7a728b395faa](https://github.com/tldr-pages/tldr/commit/7a728b395faa928a84649ebf1f5996da3c772639)

