---
author: ['Guido Lena Cota']
date: 1570361130
title: "git bisect, TLDR Pages"
description: "git bisect, Usa la ricerca binaria per trovare il commit che ha introdotto un bug."
categories: "common"
---
> Git salta automaticamente avanti ed indietro nell'albero dei commit per restringere progressivamente il campo fino al commit colpevole.

> Maggiori informazioni: <https://git-scm.com/docs/git-bisect>.

- Avvia una ricerca su un intervallo di commit definito dal commit "cattivo" contenente il bug ed un altro commit "buono" privo del bug (solitamente più vecchio):

```bash
git bisect start commit_cattivo commit_buono
```

- Contrassegna ogni commit selezionato da `git bisect` come "bad" (cattivo) o "good" (buono) dopo averlo testato per verificare la presenza del bug:

```bash
git bisect good|bad
```

- Una volta che `git bisect` ha individuato il commit che ha introdotto il bug, termina la sessione di ricerca e torna al ramo precedente:

```bash
git bisect reset
```

- Ignora un commit durante la ricerca (ad esempio uno che fallisce i test per un motivo diverso dal bug ricercato):

```bash
git bisect skip
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

