---
author: ['Stig124', 'Marco Bonelli']
date: 1625841955
title: "as"
description: "as, Assembler GNU multiplataforma."
categories: "linux"
---
> Seu objetivo inicial é realizar o montagem do arquivo gerado pelo `gcc` para ser utilizado pelo `ld`.

> Mais informações: <https://manned.org/as>.

- Realizar a montagem de um arquivo, o resultado dessa operação será gravado no arquivo a.out:

```bash
as arquivo.s
```

- Realizar a montagem de um arquivo, o resultado dessa operação será gravado em um arquivo específico:

```bash
as arquivo.s -o saida.o
```

- Realizar a montagem de um arquivo rapidamente, pois ignora o pré-processamento de comentários e espaços em branco. (Deve ser utilizado apenas em compiladores confiáveis):

```bash
as -f arquivo.s
```

- Adiciona um caminho na lista de diretórios onde será realizada a busca por arquivos especificados na diretiva .include:

```bash
as -I caminho_para_o_diretorio arquivo.s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

