---
author: ['Gabriel Rodrigues']
date: 1634021667
title: "dust, TLDR Pages"
description: "dust, Dust oferece uma visão geral de quais diretórios estão usando espaço em disco."
categories: "common"
---
> Mais informações: <https://github.com/bootandy/dust>.

- Exibe informações para o diretório atual:

```bash
dust
```

- Exibe informações para uma lista de diretórios separados por espaço:

```bash
dust caminho/para/diretório1 caminho/para/diretório2
```

- Exibe 30 diretórios (o padrão é 21):

```bash
dust --number-of-lines 30
```

- Exibe informações para o diretório atual, com até 3 níveis de profundidade:

```bash
dust --depth 3
```

- Exibe os maiores diretórios no topo em ordem decrescente:

```bash
dust --reverse
```

- Ignora todos os arquivos e diretórios com um nome específico:

```bash
dust --ignore-directory arquivo_ou_nome_do_diretório
```

- Não exibe barras de porcentagem e porcentagens:

```bash
dust --no-percent-bars
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Gabriel Rodrigues](mailto:78451370+gabxyz@users.noreply.github.com) | dust, rustc: add pt_BR translation (#6848) | 2021-10-12T08:54:27 | [62be7935aa42](https://github.com/tldr-pages/tldr/commit/62be7935aa422a8bde7099fc04b89c0a0788f6c5)

