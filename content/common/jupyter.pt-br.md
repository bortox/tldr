---
author: ['André Viana']
date: 1636017030
title: "jupyter, TLDR Pages"
description: "jupyter, Aplicação web para criar e compartilhar documentos que contem código, visualizações e anotações."
categories: "common"
---
> Usado principalmente para análise de dados, computação científica e aprendizado de máquinas (machine learning).

> Mais informações: <https://jupyter.org>.

- Inicia um servidor de notebooks Jupyter no diretório atual:

```bash
jupyter notebook
```

- Abre um caderno Jupyter específico:

```bash
jupyter notebook exemplo.ipynb
```

- Exporta um caderno Jupyter específico para outro formato:

```bash
jupyter nbconvert --to html|markdown|pdf|script exemplo.ipynb
```

- Inicia um servidor em uma porta específica:

```bash
jupyter notebook --port=porta
```

- Lista de servidores de notebooks atualmente em funcionamento:

```bash
jupyter notebook list
```

- Para o servidor atualmente em funcionamento:

```bash
jupyter notebook stop
```

- Inicia o JupyterLab, se instalado, no diretório atual:

```bash
jupyter lab
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[André Viana](mailto:andrebermudesviana@gmail.com) | jupyter: add pt_BR translation (#7285) | 2021-11-04T10:10:30 | [924846af6ed9](https://github.com/tldr-pages/tldr/commit/924846af6ed921aef5de92542a0a8345ac82addc)

