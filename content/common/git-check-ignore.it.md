---
author: ['Lucas Gabriel Schneider', 'Guido Lena Cota']
date: 1612112718
title: "git check-ignore"
description: "git check-ignore, Analizza ed esegui il debug di '.gitignore' e dei file esclusi."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-check-ignore>.

- Verifica se un file o una cartella sono ignorati:

```bash
git check-ignore percorso/al/file_o_cartella
```

- Verifica se più file o cartelle sono ignorati:

```bash
git check-ignore percorso/al/file percorso/alla/cartella
```

- Leggi i percorsi di file o cartelle da stdin (uno per riga) invece che dalla riga di comando:

```bash
git check-ignore --stdin < percorso/alla/lista_dei_file_o_cartelle
```

- Non controllare nell'indice (usato per determinare il motivo per cui alcuni percorsi non sono ignorati):

```bash
git check-ignore --no-index percorsi/ai/file_o_cartelle
```

- Includi dettagli sul pattern corrispondente per ogni percorso specificato:

```bash
git check-ignore --verbose percorsi/ai/file_o_cartelle
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

