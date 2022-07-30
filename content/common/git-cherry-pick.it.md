---
author: ['Guido Lena Cota']
date: 1570361130
title: "git cherry-pick"
description: "git cherry-pick, Applica al ramo corrente le modifiche introdotte da commit esistenti."
categories: "common"
---
> Per applicare le modifiche ad un altro ramo, usa prima `git checkout` per passare al ramo desiderato.

> Maggiori informazioni: <https://git-scm.com/docs/git-cherry-pick>.

- Applica un commit al ramo corrente:

```bash
git cherry-pick commit
```

- Applica una sequenza di commit al ramo corrente (vedi anche `git rebase --onto`):

```bash
git cherry-pick commit_iniziale~..commit_finale
```

- Applica un insieme di commit non sequenziali al ramo corrente:

```bash
git cherry-pick commit_1 commit_2
```

- Aggiungi le modifiche introdotte da un commit alla cartella di lavoro, ma senza creare un nuovo commit:

```bash
git cherry-pick -n commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

