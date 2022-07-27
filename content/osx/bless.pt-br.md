---
author: ['Andreia Bohner']
date: 1658135504
title: "bless, TLDR Pages"
description: "bless, Define a capacidade de inicialização por volume e as opções de disco de inicialização. Set volume boot capability and startup disk options."
categories: "osx"
---
> Mais informações: <https://ss64.com/osx/bless.html>.

- Definir um volume somente com Mac OS X ou Darwin, e criar os arquivos BootX e `boot.efi` se necessário:

```bash
bless --folder /Volumes/Mac OS X/System/Library/CoreServices --bootinfo --bootefi
```

- Definir um volume contendo Mac OS 9 ou Mac OS X como o volume ativo:

```bash
bless --mount /Volumes/Mac OS --setBoot
```

- Definir o sistema para NetBoot e transmitir para um servidor disponível:

```bash
bless --netboot --server bsdp://255.255.255.255
```

- Coletar informações sobre o volume atualmente selecionado (conforme determinado pelo firmware), adequado para piping para um programa capaz de analisar listas de propriedades:

```bash
bless --info --plist
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | bless: add pt_BR translation | 2022-07-18T11:11:44 | [43ecd0cd595d](https://github.com/tldr-pages/tldr/commit/43ecd0cd595dbe1e06221a8276514245bfb36b95)

