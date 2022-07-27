---
author: ['Felix Yan', 'Austin Shapiro', 'pxgamer', 'Jay Piamjariyakul', 'bl-ue', 'marchersimon']
date: 1621541621
title: "speedtest-cli, TLDR Pages"
description: "speedtest-cli, Unofficial command-line interface for testing internet bandwidth using https://speedtest.net."
categories: "common"
---
> See also `speedtest` for the official CLI.

> More information: <https://github.com/sivel/speedtest-cli>.

- Run a speed test:

```bash
speedtest-cli
```

- Run a speed test and display values in bytes, instead of bits:

```bash
speedtest-cli --bytes
```

- Run a speed test using `HTTPS`, instead of `HTTP`:

```bash
speedtest-cli --secure
```

- Run a speed test without performing download tests:

```bash
speedtest-cli --no-download
```

- Run a speed test and generate an image of the results:

```bash
speedtest-cli --share
```

- List all `speedtest.net` servers, sorted by distance:

```bash
speedtest-cli --list
```

- Run a speed test to a specific speedtest.net server:

```bash
speedtest-cli --server server_id
```

- Run a speed test and display the results as JSON (suppresses progress information):

```bash
speedtest-cli --json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | speedtest, speedtest-cli: refresh (#5781) * speedtest: refresh * update pages * Remove additional whitespace Co-authored-by: Axel [...] | 2021-05-10T11:04:20 | [abfc6f29dfa1](https://github.com/tldr-pages/tldr/commit/abfc6f29dfa165275794e43666373b196baedf04)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | speedtest-cli: update grammar, links, and token syntax (#5284) | 2021-02-26T11:39:06 | [fca445d12e8d](https://github.com/tldr-pages/tldr/commit/fca445d12e8d67ec960add4cbf202f189a48e9b3)
[Jay Piamjariyakul](mailto:j.piamjariyakul@outlook.com) | speedtest-cli: add --csv and --json examples (#4465) | 2020-10-05T04:10:29 | [4e4622b40d42](https://github.com/tldr-pages/tldr/commit/4e4622b40d42889bcc064316896ee7ef3a02b2f3)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | speedtest-cli: add link to homepage | 2019-05-29T14:41:10 | [8f85229a38d2](https://github.com/tldr-pages/tldr/commit/8f85229a38d25be92879eba23c50b6b1c567b530)
[Felix Yan](mailto:felixonmars@archlinux.org) | speedtest-cli: correct a typo | 2018-06-09T06:41:16 | [35d86d5e9676](https://github.com/tldr-pages/tldr/commit/35d86d5e96769fdaa0132156b136412cd3ad2511)
[Austin Shapiro](mailto:truescarsz@gmail.com) | speedtest-cli: number -> id | 2017-12-13T05:01:22 | [700753749327](https://github.com/tldr-pages/tldr/commit/7007537493275cb8f031da25cdfc4d3962e6cd5d)
[Austin Shapiro](mailto:truescarsz@gmail.com) | speedtest-cli: fix punctuation | 2017-12-13T01:48:18 | [53c4ef46ca32](https://github.com/tldr-pages/tldr/commit/53c4ef46ca32dc3893c9fbedf8c45e7c58e8424a)
[Austin Shapiro](mailto:truescarsz@gmail.com) | speedtest-cli: add page | 2017-12-13T01:42:45 | [54da3ad2de05](https://github.com/tldr-pages/tldr/commit/54da3ad2de052c7684b05bf4cf7f043ddf3bc65b)

