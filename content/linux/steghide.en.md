---
author: ['Alex', 'Seth Falco']
date: 1629050349
title: "steghide, TLDR Pages"
description: "steghide, Steganography tool for JPEG, BMP, WAV and AU file formats."
categories: "linux"
---
> More information: <https://github.com/StefanoDeVuono/steghide>.

- Embed data in a PNG, prompting for a passphrase:

```bash
steghide embed --coverfile path/to/image.png --embedfile path/to/data.txt
```

- Extract data from a WAV audio file:

```bash
steghide extract --stegofile path/to/sound.wav
```

- Display file information, trying to detect an embedded file:

```bash
steghide info path/to/file.jpg
```

- Embed data in a JPEG image, using maximum compression:

```bash
steghide embed --coverfile path/to/image.jpg --embedfile path/to/data.txt --compress 9
```

- Get the list of supported encryption algorithms and modes:

```bash
steghide encinfo
```

- Embed encrypted data in a JPEG image, e.g. with Blowfish in CBC mode:

```bash
steghide embed --coverfile path/to/image.jpg --embedfile path/to/data.txt --encryption blowfish|... cbc|...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Alex](mailto:alexandre.dhondt@gmail.com) | steghide: add page (#3950) | 2020-04-04T12:26:43 | [e409ab72bd20](https://github.com/tldr-pages/tldr/commit/e409ab72bd20e42853a14371e96f55a52c7d4d0a)

