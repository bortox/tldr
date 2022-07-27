---
author: ['larissa maruyama']
date: 1634631779
title: "chmod, TLDR Pages"
description: "chmod, Muda a permissão de acesso de um arquivo ou diretório."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/chmod>.

- Dá ao [u]suário dono de um arquivo o direito de e[x]ecutá-lo:

```bash
chmod u+x arquivo
```

- Dá ao [u]suário direitos para le[r] e [w]escrever em um arquivo/diretório:

```bash
chmod u+rw arquivo_ou_diretorio
```

- Remove direitos e[x]ecutáveis de um [g]rupo:

```bash
chmod g-x arquivo
```

- Dá a [a]todos os usuários direitos para le[r] e e[x]ecutar:

```bash
chmod a+rx arquivo
```

- Dá para [o]utros (que não estejam no grupo do proprietário do arquivo) os mesmos direitos que o [g]rupo:

```bash
chmod o=g arquivo
```

- Remove todos os direitos de [o]utros:

```bash
chmod o= arquivo
```

- Muda recursivamente as permissões, dando para [g]rupo e [o]utros a habilidade para [w]escrever:

```bash
chmod -R g+w,o+w diretorio
```

- Recursivamente concede a [a]todos os usuários permissões de leitu[r]a para arquivos e e[X]ecute permissões para sub-diretórios dentro de um diretório:

```bash
chmod -R a+rX diretorio
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[larissa maruyama](mailto:54145084+snorlara@users.noreply.github.com) | chmod: add pt_BR translation (#7024) | 2021-10-19T10:22:59 | [8d2a2629344c](https://github.com/tldr-pages/tldr/commit/8d2a2629344cffcee2c2c9509e2f131b8af4ca44)

