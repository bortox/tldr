---
author: ['Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1629110041
title: "mimetype"
description: "mimetype, Automatically determine the MIME type of a file."
categories: "linux"
---
> More information: <https://manned.org/mimetype>.

- Print the MIME type of a given file:

```bash
mimetype path/to/file
```

- Display only the MIME type, and not the filename:

```bash
mimetype --brief path/to/file
```

- Display a description of the MIME type:

```bash
mimetype --describe path/to/file
```

- Determine the MIME type of stdin (does not check a filename):

```bash
some_command | mimetype --stdin
```

- Display debug information about how the MIME type was determined:

```bash
mimetype --debug path/to/file
```

- Display all the possible MIME types of a given file in confidence order:

```bash
mimetype --all path/to/file
```

- Explicitly specify the 2-letter language code of the output:

```bash
mimetype --language path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mimetype: add page (#3169) | 2019-07-04T10:03:38 | [0c3b3d9f1684](https://github.com/tldr-pages/tldr/commit/0c3b3d9f16846c7882a0c0649b9c473034f8cf62)

