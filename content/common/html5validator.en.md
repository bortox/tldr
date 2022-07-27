---
author: ['bl-ue', 'Owen Voke']
date: 1621541621
title: "html5validator, TLDR Pages"
description: "html5validator, A command-line tool for testing HTML5 validity."
categories: "common"
---
> More information: <https://github.com/svenkreiss/html5validator>.

- Validate a specific file:

```bash
html5validator path/to/file
```

- Validate all HTML files in a specific directory:

```bash
html5validator --root path/to/directory
```

- Show warnings as well as errors:

```bash
html5validator --show-warnings path/to/file
```

- Match multiple files using a glob pattern:

```bash
html5validator --root path/to/directory --match "*.html *.php"
```

- Ignore specific directory names:

```bash
html5validator --root path/to/directory --blacklist "node_modules vendor"
```

- Output the results in a specific format:

```bash
html5validator --format gnu|xml|json|text path/to/file
```

- Output the log at a specific verbosity level:

```bash
html5validator --root path/to/directory --log debug|info|warning
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:owzie123@gmail.com) | html5validator: add page (#3558) | 2019-11-14T18:01:22 | [4c01dc5b0cad](https://github.com/tldr-pages/tldr/commit/4c01dc5b0cadb87cf59ca3f15bbddc882c1aca5e)

