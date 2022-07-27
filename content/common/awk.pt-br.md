---
author: ['alexsantee']
date: 1635359952
title: "awk, TLDR Pages"
description: "awk, Uma linguagem de programação versátil para trabalhar com arquivos."
categories: "common"
---
> Mais informações: <https://github.com/onetrueawk/awk>.

- Imprime a quinta coluna (também chamada de campo) em um arquivo separado por espaços:

```bash
awk '{print $5}' nome_do_arquivo
```

- Imprime a segunda coluna das linhas contendo "foo" em um arquivo separado por espaços:

```bash
awk '/foo/ {print $2}' nome_do_arquivo
```

- Imprime a última coluna de cada linha em um arquivo, usando vírgula (ao invés de espaço) como separador de campo:

```bash
awk -F ',' '{print $NF}' nome_do_arquivo
```

- Soma os valores da primeira coluna de um arquivo e imprime o total:

```bash
awk '{s+=$1} END {print s}' nome_do_arquivo
```

- Imprime de três em três linhas a partir da primeira:

```bash
awk 'NR%3==1' nome_do_arquivo
```

- Imprime diferentes valores baseado em condições:

```bash
awk '{if ($1 == "foo") print "Correspondência completa foo"; else if ($1 ~ "bar") print "Correspondência parcial bar"; else print "Baz"}' nome_do_arquivo
```

- Imprime todas as linhas em que a 10ª coluna é igual a um dado valor:

```bash
awk '($10 == valor)'
```

- Imprime todas as linhas em que o valor da décima coluna está entre um mínimo e um máximo:

```bash
awk '($10 >= valor_minimo && $10 <= valor_maximo)'
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[alexsantee](mailto:40058461+alexsantee@users.noreply.github.com) | awk: add pt_BR translation (#7169) | 2021-10-27T20:39:12 | [7093cf66760a](https://github.com/tldr-pages/tldr/commit/7093cf66760a5d36e4fcacab002b01ce3c603809)

