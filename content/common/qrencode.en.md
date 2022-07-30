---
author: ['bl-ue', 'Florian Ströger', 'Vaarnan Drolia']
date: 1612026198
title: "qrencode"
description: "qrencode, QR Code generator. Supports PNG and EPS."
categories: "common"
---
> More information: <https://fukuchi.org/works/qrencode>.

- Convert a string to a QR code and save to an output file:

```bash
qrencode -o path/to/output_file.png string
```

- Convert an input file to a QR code and save to an output file:

```bash
qrencode -o path/to/output_file.png -r path/to/input_file
```

- Convert a string to a QR code and print it in terminal:

```bash
qrencode -t ansiutf8 string
```

- Convert input from pipe to a QR code and print it in terminal:

```bash
echo string | qrencode -t ansiutf8
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Florian Ströger](mailto:florian@florianstroeger.com) | qrencode: add print to terminal examples (#3823) | 2020-02-05T10:56:35 | [e1355b2e8749](https://github.com/tldr-pages/tldr/commit/e1355b2e8749ea4b4dc98f430f5bc01ae877e339)
[Vaarnan Drolia](mailto:vellvisher@users.noreply.github.com) | qrencode: add page (#3618) | 2019-11-28T22:12:20 | [acb14d810930](https://github.com/tldr-pages/tldr/commit/acb14d810930c18d6c26c259e87c0f7a1c7e4b77)

