---
author: ['Niklas', 'Ricardo H H Kojo']
date: 1635215179
title: "yaourt"
description: "yaourt, Utilitário de Arch Linux para compilaçào de pacotes AUR (Arch User Repository)."
categories: "linux"
---
> Mais informações: <https://linuxcommandlibrary.com/man/yaourt>.

- Sincroniza e atualiza todos os pacotes (incluindo AUR):

```bash
yaourt -Syua
```

- Instala um novo pacote (incluindo AUR):

```bash
yaourt -S nome_do_pacote
```

- Remove um pacote e suas dependências (incluindo pacotes AUR):

```bash
yaourt -Rs nome_do_pacote
```

- Procura no banco de dados de pacotes por uma palavra-chave (incluindo AUR):

```bash
yaourt -Ss nome_do_pacote
```

- Lista pacotes instalados, versões, e repositórios (pacotes AUR serão listados sob como repositório 'local'):

```bash
yaourt -Q
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Niklas](mailto:derNiklaas@users.noreply.github.com) | yank, yaourt: add more information link (#7049) | 2021-10-26T04:26:19 | [bf5c13a00d3b](https://github.com/tldr-pages/tldr/commit/bf5c13a00d3b256646326a4d3bfd23fddc5dbed3)
[Ricardo H H Kojo](mailto:ricardo.kojo.dev@gmail.com) | yaourt: add pt_BR translation Signed-off-by: Ricardo H H Kojo <ricardo.kojo.dev@gmail.com> | 2021-10-13T14:01:46 | [894f68eaf5fd](https://github.com/tldr-pages/tldr/commit/894f68eaf5fdb0a968d2d9e3e13411309aa78041)

