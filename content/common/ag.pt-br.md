---
author: ['João C Fukuda']
date: 1633878106
title: "ag"
description: "ag, The Silver Searcher. Parecido com o ack, mas com um foco em ser ainda mais rápido."
categories: "common"
---
> Mais informações: <https://github.com/ggreer/the_silver_searcher>.

- Acha arquivos que contém "foo" e imprime as linhas correspondentes no contexto:

```bash
ag foo
```

- Acha arquivos que contém "foo" em um diretório específico:

```bash
ag foo caminho/para/arquivo
```

- Acha arquivos que contém "foo", mas lista somente os nomes dos arquivos:

```bash
ag -l foo
```

- Acha arquivos que contém "FOO" sem diferença de caixa e imprime somente o correspondente em vez de a linha inteira:

```bash
ag -i -o FOO
```

- Acha "foo" em arquivos cujo nome corresponde a "bar":

```bash
ag foo -G bar
```

- Acha arquivos cujo conteúdo corresponde à expressão regular:

```bash
ag '^ba(r|z)$'
```

- Acha arquivos cujo nome corresponde a "foo":

```bash
ag -g foo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[João C Fukuda](mailto:37672942+JoaoFukuda@users.noreply.github.com) | ag: add pt_BR translation (#6887) | 2021-10-10T17:01:46 | [ab8834bb8ce9](https://github.com/tldr-pages/tldr/commit/ab8834bb8ce9586aec2129f892a21eb11e6e4e81)

