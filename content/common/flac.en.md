---
author: ['AberDerBart', 'Agniva De Sarker', 'pxgamer', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "flac, TLDR Pages"
description: "flac, Encodes, decodes and tests FLAC files."
categories: "common"
---
> More information: <https://xiph.org/flac>.

- Encode a WAV file to FLAC (this will create a FLAC file in the same location as the WAV file):

```bash
flac path/to/file.wav
```

- Encode a WAV file to FLAC, specifying the output file:

```bash
flac -o path/to/output.flac path/to/file.wav
```

- Decode a FLAC file to WAV, specifying the output file:

```bash
flac -d -o path/to/output.wav path/to/file.flac
```

- Test a FLAC file for the correct encoding:

```bash
flac -t path/to/file.flac
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | flac: add link to homepage | 2019-06-07T23:58:59 | [4b40effe4b38](https://github.com/tldr-pages/tldr/commit/4b40effe4b38f066170cfcda696c85980a85bb54)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Fix teensy grammatical mistake | 2018-01-09T19:39:53 | [5b9bafc4ac46](https://github.com/tldr-pages/tldr/commit/5b9bafc4ac46748559f8b4b7796649c7e33e4205)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | flac: match conventions - Removed preceding / from file paths - Made the output flag to be consistent on both examples -Clarified the [...] | 2018-01-09T09:26:49 | [75ce4244d599](https://github.com/tldr-pages/tldr/commit/75ce4244d599ab6fb81fda50b42413ceffc0d9d7)
[AberDerBart](mailto:j.grosse-holz@gmx.de) | flac: introduce -o/--output-name with encode | 2018-01-09T09:15:57 | [b4d2f5829874](https://github.com/tldr-pages/tldr/commit/b4d2f582987449028906c0e304a4a599018aefaf)
[AberDerBart](mailto:j.grosse-holz@gmx.de) | flac: add page | 2018-01-09T01:47:05 | [c28331964b9f](https://github.com/tldr-pages/tldr/commit/c28331964b9f5ad05a841615f7ce8ff68ca0547b)

