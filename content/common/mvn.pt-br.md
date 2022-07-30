---
author: ['Marco Bonelli', 'Nicolas Kosinski', 'marchersimon']
date: 1633112881
title: "mvn"
description: "mvn, Ferramenta para a criação e gerenciamento de projetos Java."
categories: "common"
---
> Mais informações: <https://maven.apache.org>.

- Compilar um projeto:

```bash
mvn compile
```

- Criar um artefato de distribuição utilizando o formato espeficado no `pom.xml`, por exemplo o formato `jar`:

```bash
mvn package
```

- Criar um artefato de distribuição sem executar testes unitários:

```bash
mvn package -DskipTests
```

- Instalar um artefato gerado em um repositório local:

```bash
mvn install
```

- Apagar artefatos gerados no diretório `target`:

```bash
mvn clean
```

- Executar as fases `clean` e `package` em um projeto:

```bash
mvn clean package
```

- Executar as fases `clean` e `package` em um projeto utilizando um perfil:

```bash
mvn clean -Pperfil package
```

- Executar uma classe que possua o método `main`:

```bash
mvn exec:java -Dexec.mainClass="nome.do.pacote.classe" -Dexec.args="arg1 arg2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | mvn: simplify skip unit tests (#6448) | 2021-09-01T18:39:12 | [449267ef131c](https://github.com/tldr-pages/tldr/commit/449267ef131c2d8c5269b5903682c5c4ef98ddf7)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

