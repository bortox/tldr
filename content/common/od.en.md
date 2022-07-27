---
author: ['Waldir Pimenta', 'Yuri Slobodyanyuk', 'Dario Vladović', 'yuri-sk', 'marchersimon']
date: 1617292466
title: "od, TLDR Pages"
description: "od, Display file contents in octal, decimal or hexadecimal format."
categories: "common"
---
> Optionally display the byte offsets and/or printable representation for each line.

> More information: <https://www.gnu.org/software/coreutils/od>.

- Display file using default settings: octal format, 8 bytes per line, byte offsets in octal, and duplicate lines replaced with `*`:

```bash
od path/to/file
```

- Display file in verbose mode, i.e. without replacing duplicate lines with `*`:

```bash
od -v path/to/file
```

- Display file in hexadecimal format (2-byte units), with byte offsets in decimal format:

```bash
od --format=x --address-radix=d -v path/to/file
```

- Display file in hexadecimal format (1-byte units), and 4 bytes per line:

```bash
od --format=x1 --width=4 -v path/to/file
```

- Display file in hexadecimal format along with its character representation, and do not print byte offsets:

```bash
od --format=xz --address-radix=n -v path/to/file
```

- Read only 100 bytes of a file starting from the 500th byte:

```bash
od --read-bytes 100 --skip-bytes=500 -v path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | od: add link (#5587) | 2021-03-30T15:56:07 | [28b0f3fa11d7](https://github.com/tldr-pages/tldr/commit/28b0f3fa11d76b11e53de3e7cc611f2c7036e930)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | od: overall copyedit - reworded command description - reworded example descriptions for clarity and explicitness - changed order and [...] | 2017-04-18T06:54:50 | [aa22af277ae3](https://github.com/tldr-pages/tldr/commit/aa22af277ae36c4d3c157c7f8debffc34aed8604)
[Yuri Slobodyanyuk](mailto:yuri@yurisk.info) | Update od.md yet another fix | 2017-04-18T06:54:50 | [8b79edda0c28](https://github.com/tldr-pages/tldr/commit/8b79edda0c28903e5d179358e66072330228b111)
[Yuri Slobodyanyuk](mailto:yuri@yurisk.info) | Update od.md still more fixes | 2017-04-18T06:54:50 | [aa9d4d58872f](https://github.com/tldr-pages/tldr/commit/aa9d4d58872f4c660e25169dbcf5e8acfe8e2cd9)
[yuri-sk](mailto:yuri@yurisk.info) | Update od.md | 2017-04-18T06:54:50 | [aface6c32d9a](https://github.com/tldr-pages/tldr/commit/aface6c32d9ad55bf326ba1ef4518479c2e1fadb)
[yuri-sk](mailto:yuri@yurisk.info) | Update od.md Fixed | 2017-04-18T06:54:50 | [25a9bc4ae4a0](https://github.com/tldr-pages/tldr/commit/25a9bc4ae4a07a087318ca0b33b4207c06c7fae0)
[yuri-sk](mailto:yuri@yurisk.info) | Add odd command to the common Not much to comment - https://linux.die.net/man/1/od Thanks | 2017-04-18T06:54:50 | [de1d5b05fabc](https://github.com/tldr-pages/tldr/commit/de1d5b05fabca1e9db75320c51a4c6c88dac6a5a)

