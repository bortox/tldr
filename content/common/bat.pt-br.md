---
author: ['FilipaDurao', 'Marco Bonelli']
date: 1572006427
title: "bat"
description: "bat, Imprimir e concatenar arquivos."
categories: "common"
---
> Um clone do `cat` com realce de sintaxe e integração com Git.

> Mais informações: <https://github.com/sharkdp/bat>.

- Imprimir o conteúdo de um arquivo para a saída padrão:

```bash
bat arquivo
```

- Concatenar vários arquivos em um arquivo de destino:

```bash
bat caminho/para/arquivo1 caminho/para/arquivo2 > caminho/para/arquivo_destino
```

- Numerar todas as linhas do output:

```bash
bat -n caminho/para/arquivo
```

- Realçar a sintaxe em um arquivo JSON:

```bash
bat --language json caminho/para/arquivo.json
```

- Mostrar todas as linguagens suportadas:

```bash
bat --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | bat, bg, cmus, man (pt_BR): fix broken description. | 2019-10-25T14:27:07 | [4484fd55c2ab](https://github.com/tldr-pages/tldr/commit/4484fd55c2aba7fec86030afe5429545c82b7f8c)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | bat: add pt_BR translation (#3420) | 2019-10-18T03:54:37 | [e94b291c7f66](https://github.com/tldr-pages/tldr/commit/e94b291c7f66db4b86db6070bd1ab24a8e8ac46b)

