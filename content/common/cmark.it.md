---
author: ['Waldir Pimenta', 'Marco Bonelli', 'bl-ue']
date: 1621541621
title: "cmark, TLDR Pages"
description: "cmark, Converte testo CommonMark Markdown in altri formati."
categories: "common"
---
> Maggiori informazioni: <https://github.com/commonmark/cmark>.

- Converti un file Markdown in HTML:

```bash
cmark --to html file.md
```

- Converti in LaTeX da standard input:

```bash
cmark --to latex
```

- Converti apici semplici in apici intelligenti:

```bash
cmark --smart --to html file.md
```

- Converti validando i caratteri UTF-8:

```bash
cmark --validate-utf8 file.md
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix capitalization of "LaTeX" (#5695) | 2021-04-06T14:16:08 | [a6b24e10e6c9](https://github.com/tldr-pages/tldr/commit/a6b24e10e6c93175fafe62f246e13e3641dac76c)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cmark: add Italian translation. | 2019-03-03T23:44:18 | [15e638ca64d1](https://github.com/tldr-pages/tldr/commit/15e638ca64d1eeaa1fc973aa0bf69da25630e2f0)

