---
author: ['Waldir Pimenta', 'Agniva De Sarker', 'syleung', 'Per Jørgen Walstrøm', 'Lucas Gabriel Schneider']
date: 1633350747
title: "xxd, TLDR Pages"
description: "xxd, Create a hexadecimal representation (hexdump) from a binary file, or vice-versa."
categories: "common"
---
> More information: <https://manned.org/xxd>.

- Generate a hexdump from a binary file and display the output:

```bash
xxd input_file
```

- Generate a hexdump from a binary file and save it as a text file:

```bash
xxd input_file output_file
```

- Display a more compact output, replacing consecutive zeros (if any) with a star:

```bash
xxd -a input_file
```

- Display the output with 10 columns of one octet (byte) each:

```bash
xxd -c 10 input_file
```

- Display output only up to a length of 32 bytes:

```bash
xxd -l 32 input_file
```

- Display the output in plain mode, without any gaps between the columns:

```bash
xxd -p input_file
```

- Revert a plaintext hexdump back into binary, and save it as a binary file:

```bash
xxd -r -p input_file output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/x*: add more information link (#6664) | 2021-10-04T14:32:27 | [99a72c556f56](https://github.com/tldr-pages/tldr/commit/99a72c556f563a928a10ff2c2146ad42d9af2990)
[Per Jørgen Walstrøm](mailto:per.jorgen.walstrom@nav.no) | xxd: add -a for compact output example (#4990) | 2020-11-30T13:09:35 | [4af919369e87](https://github.com/tldr-pages/tldr/commit/4af919369e872569dad5548882f8d86389235095)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: fixed typos (#2871) | 2019-04-06T14:34:03 | [9abddffd09d3](https://github.com/tldr-pages/tldr/commit/9abddffd09d33dba8c1e022085f7aa4e7ca6ce1b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | xxd: add length flag (#2034) | 2018-03-19T10:14:35 | [ddc10f1be017](https://github.com/tldr-pages/tldr/commit/ddc10f1be0178a48f87950838b564d17cbe2c7db)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xxd: reword descriptions for clarity & consistency (#1465) | 2017-09-20T17:44:36 | [e3c103f0ade0](https://github.com/tldr-pages/tldr/commit/e3c103f0ade0316dc8843826c9fbacf79f1ce234)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | xxd: add page (#1424) | 2017-07-06T18:26:44 | [a5cd2a7dc783](https://github.com/tldr-pages/tldr/commit/a5cd2a7dc7833dc786efe1d03cc8b48440ccac82)

