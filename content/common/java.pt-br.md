---
author: ['4n7hem', 'lincc']
date: 1643487459
title: "java, TLDR Pages"
description: "java, Inicializador de Programas Java."
categories: "common"
---
> Mais informações: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- Executa um arquivo Java `.class` que contém um método main, usando o nome da classe:

```bash
java nome_da_classe
```

- Executa um programa `.jar`:

```bash
java -jar arquivo.jar
```

- Executa um programa `.jar`, com o debugger tentando conectar-se na porta 5005:

```bash
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar arquivo.jar
```

- Exiba a versão do JDK, JRE e Hotspot:

```bash
java -version
```

- Exiba os comandos disponíveis do Java:

```bash
java -help
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[4n7hem](mailto:48725919+4n7hem@users.noreply.github.com) | java: add pt_BR translation (#6884) | 2021-10-10T17:04:23 | [dad226752ce9](https://github.com/tldr-pages/tldr/commit/dad226752ce90d8c65cc6289585cde78fd79b6bf)

