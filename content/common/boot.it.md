---
author: ['Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "boot"
description: "boot, Strumenti di build per il linguaggio di programmazione Clojure."
categories: "common"
---
> Maggiori informazioni: <https://github.com/boot-clj/boot>.

- Avvia una sessione REPL con il progetto o da sola:

```bash
boot repl
```

- Builda un singolo `uberjar`:

```bash
boot jar
```

- Mostra aiuto per un comando:

```bash
boot cljs --help
```

- Genera le fondamenta per un nuovo progetto basandoti su una template:

```bash
boot --dependencies boot/new new --template nome_template --name nome_progetto
```

- Builda per development (se si sta utilizzando il template boot/new):

```bash
boot dev
```

- BUilda per produzione (se si sta utilizzando il template boot/new):

```bash
boot prod
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\boot.md: add homepage | 2019-05-14T19:40:23 | [01b993bca953](https://github.com/tldr-pages/tldr/commit/01b993bca9535720fbe1d9d159447915267323be)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | boot: add Italian translation. | 2019-01-28T19:10:19 | [5dee57df4800](https://github.com/tldr-pages/tldr/commit/5dee57df48006b287d1534e88e92ac5432616fe1)

