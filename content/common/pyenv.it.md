---
author: ['Francesco Franchina']
date: 1635017799
title: "pyenv, TLDR Pages"
description: "pyenv, Passa da una distribuzione all'altra di Python in modo semplice."
categories: "common"
---
> Maggiori informazioni: <https://github.com/pyenv/pyenv>.

- Elenca i comandi disponibili:

```bash
pyenv commands
```

- Elenca tutte le distribuzioni di Python presenti nella cartella `${PYENV_ROOT}/versions`:

```bash
pyenv versions
```

- Installa una distribuzione di Python nella cartella `${PYENV_ROOT}/versions`:

```bash
pyenv install 2.7.10
```

- Disinstalla una distribuzione di Python dalla cartella `${PYENV_ROOT}/versions`:

```bash
pyenv uninstall 2.7.10
```

- Imposta la distribuzione di Python da utilizzare globalmente sulla macchina:

```bash
pyenv global 2.7.10
```

- Imposta la distribuzione di Python da utilizzare nella cartella corrente e in tutte le relative sottocartelle:

```bash
pyenv local 2.7.10
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | pyenv, pyenv-virtualenv: add Italian translation (#6980) | 2021-10-23T21:36:39 | [f9c01797e7bd](https://github.com/tldr-pages/tldr/commit/f9c01797e7bdef17dea1c06f88ee7900b48b9017)

