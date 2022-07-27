---
author: ['Pierre Rudloff', 'pxgamer', 'Owen Voke']
date: 1601904906
title: "phpcs, TLDR Pages"
description: "phpcs, Tokenize PHP, JavaScript and CSS files to detect violations of a defined set of coding standards."
categories: "common"
---
> More information: <https://github.com/squizlabs/PHP_CodeSniffer>.

- Sniff the specified directory for issues (defaults to the PEAR standard):

```bash
phpcs path/to/directory
```

- Display a list of installed coding standards:

```bash
phpcs -i
```

- Specify a coding standard to validate against:

```bash
phpcs path/to/directory --standard standard
```

- Specify comma-separated file extensions to include when sniffing:

```bash
phpcs path/to/directory --extensions file_extension(s)
```

- Specify the format of the output report (e.g. `full`, `xml`, `json`, `summary`):

```bash
phpcs path/to/directory --report format
```

- Set config variables to be used during the process:

```bash
phpcs path/to/directory --config-set key value
```

- A comma-separated list of files to load before processing:

```bash
phpcs path/to/directory --bootstrap file(s)
```

- Don't recurse into subdirectories:

```bash
phpcs path/to/directory -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpcs, phpcbf: explain that file extensions are comma-separated (#4429) * phpcs, phpcbf: explain that file extensions are comma- [...] | 2020-10-05T15:35:06 | [3bdfdd2bfd00](https://github.com/tldr-pages/tldr/commit/3bdfdd2bfd0056d128a01df89b09c872fc551ce5)
[pxgamer](mailto:owzie123@gmail.com) | phpcs: add link to homepage | 2019-05-31T20:47:40 | [f4596cb5b67d](https://github.com/tldr-pages/tldr/commit/f4596cb5b67d37aa76987a9b1237cd4c996383a9)
[Owen Voke](mailto:owzie123@gmail.com) | phpcs: add page (#1970) * phpcs: add page * phpcs: mention the default coding standard (PEAR) * Fix teensy grammatical mistake * Fix [...] | 2018-02-10T13:07:08 | [32c8746ede0d](https://github.com/tldr-pages/tldr/commit/32c8746ede0dd6a4cd65d4872e00762f950072e7)

