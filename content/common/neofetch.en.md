---
author: ['Roman Rodriguez', 'pxgamer']
date: 1559676580
title: "neofetch, TLDR Pages"
description: "neofetch, CLI tool to display information about your operating system, software and hardware."
categories: "common"
---
> More information: <https://github.com/dylanaraps/neofetch>.

- Return the default config, and create it if it's the first time the program runs:

```bash
neofetch
```

- Trigger an info line from appearing in the output, where 'infoname' is the function name in the config file, e.g. memory:

```bash
neofetch --enable|disable infoname
```

- Hide/Show OS architecture:

```bash
neofetch --os_arch on|off
```

- Enable/Disable CPU brand in output:

```bash
neofetch --cpu_brand on|off
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | neofetch: add link to homepage | 2019-06-04T21:29:40 | [277e9c3f2aa2](https://github.com/tldr-pages/tldr/commit/277e9c3f2aa2c95c7b88fd13a7445f20508f0596)
[Roman Rodriguez](mailto:romanrodriguez@users.noreply.github.com) | neofetch: add page (#2147) | 2018-06-25T20:58:24 | [5ef55e6fc44d](https://github.com/tldr-pages/tldr/commit/5ef55e6fc44ddb75672469a9403e49702bc27753)

