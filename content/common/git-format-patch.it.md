---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider']
date: 1612112718
title: "git format-patch, TLDR Pages"
description: "git format-patch, Prepara file .patch. Utile per l'invio di commit via email."
categories: "common"
---
> Vedi anche `git am`, che permette di applicare file .patch.

> Maggiori informazioni: <https://git-scm.com/docs/git-format-patch>.

- Crea un file `.patch` (il nome è assegnato automaticamente) con i commit non ancora inviati al repository remoto:

```bash
git format-patch origin
```

- Scrivi su stdout un file `.patch` per l'intervallo di commit definito dai due commit dati:

```bash
git format-patch --stdout commit_1..commit_2
```

- Scrivi un file `.patch` per gli ultimi 3 commit:

```bash
git format-patch -3
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | git-format-patch: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [99e35b2a2cb8](https://github.com/tldr-pages/tldr/commit/99e35b2a2cb8533b2d990c2581c23e5f8b08b2fb)

