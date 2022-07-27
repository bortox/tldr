---
author: ['Guido Lena Cota', 'pxgamer', 'Hayden Schiff']
date: 1601832818
title: "mitmdump, TLDR Pages"
description: "mitmdump, View, record, and programmatically transform HTTP traffic."
categories: "common"
---
> The command-line counterpart to mitmproxy.

> More information: <https://docs.mitmproxy.org/stable/overview-tools/#mitmdump>.

- Start a proxy and save all output to a file:

```bash
mitmdump -w filename
```

- Filter a saved traffic file to just POST requests:

```bash
mitmdump -nr input_filename -w output_filename "~m post"
```

- Replay a saved traffic file:

```bash
mitmdump -nc filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | mitmdump: add link to homepage | 2019-06-04T21:29:40 | [eaa37890b053](https://github.com/tldr-pages/tldr/commit/eaa37890b0536fd1490edde3e7a2ee072ba7e7bf)
[Hayden Schiff](mailto:oxguy3@gmail.com) | mitmdump: add page | 2016-01-28T21:36:32 | [9d7a09ebcc6c](https://github.com/tldr-pages/tldr/commit/9d7a09ebcc6cca3623b993c9ac0c4247ad767e00)

