---
author: ['Marco Bonelli']
date: 1560123302
title: "alex, TLDR Pages"
description: "alex, Uno strumento per individuare frasi scritte in modo insensibile o sconsiderato."
categories: "common"
---
> Aiuta a trovare termini che favoriscono un certo genere, legati alla razza, religiosamente inappropriati, o simili termini non equi in un testo.

> Maggiori informazioni: <https://github.com/get-alex/alex>.

- Analizza testo da standard input:

```bash
echo Frase da analizzare | alex --stdin
```

- Analizza tutti i file nella directory corrente:

```bash
alex
```

- Analizza uno specifico file:

```bash
alex file.md
```

- Analizza tutti i file Markdown eccetto `esempio.md`:

```bash
alex *.md !esempio.md
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | alex: add Italian translation. | 2019-06-10T01:35:02 | [99c3fe26fa9a](https://github.com/tldr-pages/tldr/commit/99c3fe26fa9a2769ac8929dd20c03124cb669cc8)

