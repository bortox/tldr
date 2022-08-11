---
author: ['Muhammad Falak R Wani', 'Francesco Franchina']
date: 1660129032
title: "pyenv"
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

- Elenca tutte le versioni di Python che possono essere installate da upstream:

```bash
pyenv install --list
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
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | pyenv: add example to list all installable versions (#8327) * pyenv: add example to list all installable versions * pyenv: add italian [...] | 2022-08-10T12:57:12 | [86c27744b0ba](https://github.com/tldr-pages/tldr/commit/86c27744b0baa0b222363aac1905de269052d05b)
[Francesco Franchina](mailto:cescus92@gmail.com) | pyenv, pyenv-virtualenv: add Italian translation (#6980) | 2021-10-23T21:36:39 | [f9c01797e7bd](https://github.com/tldr-pages/tldr/commit/f9c01797e7bdef17dea1c06f88ee7900b48b9017)

