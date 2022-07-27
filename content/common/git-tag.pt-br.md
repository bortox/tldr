---
author: ['Pedro Zaroni']
date: 1635217833
title: "git tag, TLDR Pages"
description: "git tag, Cria, exibe, exclui ou verifica tags."
categories: "common"
---
> Uma tag é uma referência estática para um commit específico.

> Mais informações: <https://git-scm.com/docs/git-tag>.

- Exibe todas as tags:

```bash
git tag
```

- Crie uma tag com o nome fornecido apontando para o commit atual:

```bash
git tag nome_da_tag
```

- Crie uma tag com o nome fornecido apontando para um determinado commit:

```bash
git tag nome_da_tag commit
```

- Cria uma tag anotada com a mensagem fornecida:

```bash
git tag nome_da_tag -m mensagem_da_tag
```

- Exclui a tag com o nome fornecido:

```bash
git tag -d nome_da_tag
```

- Obtenha tags atualizadas do upstream:

```bash
git fetch --tags
```

- Liste todas as tags cujos ancestrais incluem um determinado commit:

```bash
git tag --contains commit
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Pedro Zaroni](mailto:pedro.zaroni@quintoandar.com.br) | git-tag: add pt_BR translation (#7197) | 2021-10-26T05:10:33 | [c522e9574aa0](https://github.com/tldr-pages/tldr/commit/c522e9574aa06b17ed6638ff0e7c9a3d71c1eb65)

