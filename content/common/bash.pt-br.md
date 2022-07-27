---
author: ['Luis Felipe Santos do Nascimento']
date: 1620319123
title: "bash, TLDR Pages"
description: "bash, Bourne-Again SHell, um interpretador de linha de comando compatível com `sh`."
categories: "common"
---
> Veja também `histexpand` para a expansão do histórico.

> Mais informações: <https://gnu.org/software/bash/>.

- Iniciar uma seção interativa do shell:

```bash
bash
```

- Executar um comando e sair:

```bash
bash -c "comando"
```

- Executar um script:

```bash
bash caminho/para/script.sh
```

- Executar um script, exibindo cada comando antes de executá-lo:

```bash
bash -x caminho/para/script.sh
```

- Executar os comandos de um script, parando de executar no primeiro erro:

```bash
bash -e caminho/para/script.sh
```

- Ler e executar comandos do stdin (entrada padrão):

```bash
bash -s
```

- Exibir a versão do Bash (`$BASH_VERSION` abrange apenas a versão sem informações da licença):

```bash
bash --version
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Luis Felipe Santos do Nascimento](mailto:luisfelipesdn12@gmail.com) | [, arduino-builder, arduino, bash, clear: add pt-BR translation (#5874) | 2021-05-06T18:38:43 | [0a5e31e1c7f3](https://github.com/tldr-pages/tldr/commit/0a5e31e1c7f3a48ec206ca07bb1ffb1cd0fb39c0)

