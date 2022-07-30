---
author: ['Lucas Gabriel Schneider', 'Ivan Aracki', 'Marco Bonelli']
date: 1612112718
title: "alex"
description: "alex, A tool that catches insensitive, inconsiderate writing."
categories: "common"
---
> It helps you find gender favouring, polarising, race related, religion inconsiderate, or other unequal phrasing in text.

> More information: <https://github.com/get-alex/alex>.

- Analyze text from stdin:

```bash
echo His network looks good | alex --stdin
```

- Analyze all files in the current directory:

```bash
alex
```

- Analyze a specific file:

```bash
alex textfile.md
```

- Analyze all Markdown files except `example.md`:

```bash
alex *.md !example.md
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | change markdown to Markdown (#5049) | 2020-12-29T12:45:05 | [8b80cf08b84a](https://github.com/tldr-pages/tldr/commit/8b80cf08b84aec781c99c2a42c7acf95bab446cf)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | alex: add page (#2970) | 2019-05-02T18:22:15 | [e2d295f3e443](https://github.com/tldr-pages/tldr/commit/e2d295f3e443bb7859717764c73a718c0a1a0880)

