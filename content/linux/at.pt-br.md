---
author: ['bl-ue', 'Marco Bonelli']
date: 1617130906
title: "at"
description: "at, Executa comandos em um determinado momento."
categories: "linux"
---
> Mais informações: <https://man.archlinux.org/man/at.1>.

- Iniciar o prompt `at` para que um novo conjunto de comandos seja agendado, pressione `Ctrl + D` para salvar e sair:

```bash
at hh:mm:ss
```

- Executar os comandos e enviar o resultado por e-mail utilizando algum programa de envio de e-mail local, por exemplo o sendmail:

```bash
at hh:mm:ss -m
```

- Executar um script em um determinado momento:

```bash
at hh:mm:ss -f caminho_para_o_script
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

