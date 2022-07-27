---
author: ['Pierre Rudloff']
date: 1601904906
title: "phpcbf, TLDR Pages"
description: "phpcbf, Fix violations detected by phpcs."
categories: "common"
---
> More information: <https://github.com/squizlabs/PHP_CodeSniffer>.

- Fix issues in the specified directory (defaults to the PEAR standard):

```bash
phpcbf path/to/directory
```

- Display a list of installed coding standards:

```bash
phpcbf -i
```

- Specify a coding standard to validate against:

```bash
phpcbf path/to/directory --standard standard
```

- Specify comma-separated file extensions to include when sniffing:

```bash
phpcbf path/to/directory --extensions file_extension(s)
```

- A comma-separated list of files to load before processing:

```bash
phpcbf path/to/directory --bootstrap file(s)
```

- Don't recurse into subdirectories:

```bash
phpcbf path/to/directory -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpcs, phpcbf: explain that file extensions are comma-separated (#4429) * phpcs, phpcbf: explain that file extensions are comma- [...] | 2020-10-05T15:35:06 | [3bdfdd2bfd00](https://github.com/tldr-pages/tldr/commit/3bdfdd2bfd0056d128a01df89b09c872fc551ce5)
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpcbf: add page (#4406) | 2020-10-02T12:41:24 | [c162362ee913](https://github.com/tldr-pages/tldr/commit/c162362ee9131af4616d1ea421b8301a0a4945ca)

