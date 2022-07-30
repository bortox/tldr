---
author: ['Seth Falco']
date: 1627156220
title: "resume"
description: "resume, CLI tool to easily setup a new resume."
categories: "common"
---
> More information: <https://github.com/jsonresume/resume-cli>.

- Create a new `resume.json` file in the current working directory:

```bash
resume init
```

- Validate a `resume.json` against schema tests to ensure it complies with the standard:

```bash
resume validate
```

- Export a resume locally in a stylized HTML or PDF format:

```bash
resume export path/to/html_or_pdf
```

- Start a web server that serves a local `resume.json`:

```bash
resume serve
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | resume: add page (#6241) | 2021-07-24T21:50:20 | [f81d5958e93e](https://github.com/tldr-pages/tldr/commit/f81d5958e93ee82eed575b02adc7c20f37e30dd1)

