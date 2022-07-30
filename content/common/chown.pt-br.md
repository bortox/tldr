---
author: ['alexsantee']
date: 1635360130
title: "chown"
description: "chown, Muda o usuário e grupo donos de arquivos e diretórios."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/chown>.

- Muda o usuário que é dono de um arquivo ou diretório:

```bash
chown usuario caminho/para/arquivo_ou_diretorio
```

- Muda o usuário e grupo que são donos de um arquivo/diretório:

```bash
chown usuario:grupo caminho/para/arquivo_ou_diretorio
```

- Recursivamente muda o dono de um diretório e seu conteúdo:

```bash
chown -R usuario caminho/para/diretorio
```

- Muda o dono de um link simbólico:

```bash
chown -h usuario caminho/para/symlink
```

- Muda o dono de um arquivo/diretório para ficar igual a um arquivo de referência:

```bash
chown --reference=caminho/para/arquivo_de_referencia caminho/para/arquivo_ou_diretorio
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[alexsantee](mailto:40058461+alexsantee@users.noreply.github.com) | chown: add pt_BR translation (#7162) | 2021-10-27T20:42:10 | [6be184cfe28c](https://github.com/tldr-pages/tldr/commit/6be184cfe28c20caf551222c39ec9417d2acc07d)

