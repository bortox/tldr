---
author: ['marchersimon']
date: 1633112881
title: "tree"
description: "tree, Exibe o conteúdo do diretório atual em formato de árvore."
categories: "common"
---
> Mais informações: <http://mama.indstate.edu/users/ice/tree/>.

- Exibe os arquivos e diretórios de acordo com o nível de profundidade 'num' informado (onde 1 significa o diretório atual):

```bash
tree -L num
```

- Exibe apenas diretórios:

```bash
tree -d
```

- Inclui a exibição de arquivos ocultos com colorização diferenciada:

```bash
tree -a -C
```

- Exibe a árvore sem identação, mostrando o caminho completo (usar `-N` para não escapar espaços em branco e caracteres especiais):

```bash
tree -i -f
```

- Exibe o tamanho de cada arquivo e o tamanho acumulado de cada diretório, em um formato de leitura para humanos:

```bash
tree -s -h --du
```

- Exibe arquivos em uma árvore hierárquica, utilizando um padrão coringa, e eliminando diretórios que não contêm arquivos correspondentes ao informado:

```bash
tree -P '*.txt' --prune
```

- Exibe diretórios em uma árvore hierárquica, utilizando um padrão coringa, e eliminando diretórios que não possuem ancestrais do informado:

```bash
tree -P nome_diretorio --matchdirs --prune
```

- Exibe a árvore ignorando os diretórios informados:

```bash
tree -I 'nome_diretorio1|nome_diretorio2'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

