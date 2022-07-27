---
author: ['Guido Lena Cota', 'bl-ue', 'lucas schneider']
date: 1610124748
title: "git restore, TLDR Pages"
description: "git restore, Ripristina i file dell'albero di lavoro. Richiede versioni di Git successive alla 2.23."
categories: "common"
---
> Vedi anche `git checkout`.

> Maggiori informazioni: <https://git-scm.com/docs/git-restore>.

- Ripristina un file cancellato dal contenuto del commit corrente (HEAD):

```bash
git restore percorso/al/file
```

- Ripristina un file alla versione di un commit differente:

```bash
git restore --source commit percorso/al/file
```

- Annulla le modifiche ai file nell'area di stage, ripristinandoli all'HEAD:

```bash
git restore .
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-restore: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [0263149af3d6](https://github.com/tldr-pages/tldr/commit/0263149af3d6de47b9741be4daadb0b819d1415b)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

