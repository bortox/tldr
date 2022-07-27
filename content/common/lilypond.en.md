---
author: ['marchersimon', 'Jay Piamjariyakul']
date: 1618154950
title: "lilypond, TLDR Pages"
description: "lilypond, Typeset music and/or produce MIDI from file."
categories: "common"
---
> More information: <https://lilypond.org>.

- Compile a lilypond file into a PDF:

```bash
lilypond path/to/file
```

- Compile into the specified format:

```bash
lilypond --formats=format_dump path/to/file
```

- Compile the specified file, suppressing progress updates:

```bash
lilypond -s path/to/file
```

- Compile the specified file, and also specify the output filename:

```bash
lilypond --output=path/to/output_file path/to/input_file
```

- Show the current version of lilypond:

```bash
lilypond --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[Jay Piamjariyakul](mailto:j.piamjariyakul@outlook.com) | lilypond: add page (#4500) | 2020-10-07T13:43:41 | [cbaeb655cb50](https://github.com/tldr-pages/tldr/commit/cbaeb655cb50df3622368576e29bc23fec529fe3)

