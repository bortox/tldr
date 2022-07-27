---
author: ['Paradact']
date: 1635464997
title: "echo, TLDR Pages"
description: "echo, Drukt gegeven argumenten af."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/echo>.

- Druk een tekstbericht af. Let op: aanhalingstekens zijn optimaal:

```bash
echo "Hallo Wereld"
```

- Druk een bericht af met omgevingsvariabelen:

```bash
echo "Mijn pad is $PATH"
```

- Drukt een bericht af zonder te volgen met een nieuwe regel:

```bash
echo -n "Hallo Wereld"
```

- Voeg een bericht aan een bestand toe:

```bash
echo "Hallo Wereld" >> bestand.txt
```

- Schakel interpretatie van backslash ontkoming in (speciale karakters):

```bash
echo -e "kolom 1\kolom 2"
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Paradact](mailto:44441385+Paradact@users.noreply.github.com) | echo: add Dutch translation (#7258) | 2021-10-29T01:49:57 | [52649df0b388](https://github.com/tldr-pages/tldr/commit/52649df0b3883fb56c74e0c5a6d592b3ce33df7e)

