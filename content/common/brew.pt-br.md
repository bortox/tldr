---
author: ['marchersimon']
date: 1633112881
title: "brew, TLDR Pages"
description: "brew, A versão Linux do gerenciador de pacotes Homebrew."
categories: "common"
---
> Mais informações: <https://brew.sh>.

- Buscar por fórmulas disponíveis:

```bash
brew search termo_da_busca
```

- Instalar a última versão estável de uma fórmula (utilizar `--devel` para versões de desenvolvimento):

```bash
brew install formula
```

- Listar as fórmulas instaladas:

```bash
brew list
```

- Atualizar uma fórmula instalada (se não for informado o nome de uma fórmula, todas as fórmulas serão atualizadas):

```bash
brew upgrade formula
```

- Recuperar a versão mais recente do Linuxbrew e de todas as fórmulas do GitHub:

```bash
brew update
```

- Exibir as fórmulas que possuem novas versões disponíveis:

```bash
brew outdated
```

- Exibir informações sobre uma fórmula (versão, caminho de instalação, dependências, etc.):

```bash
brew info formula
```

- Verificar a instalação local em busca de possíveis problemas:

```bash
brew doctor
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

