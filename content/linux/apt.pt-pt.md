---
author: ['Tiago Carrondo']
date: 1635810525
title: "apt, TLDR Pages"
description: "apt, Gestor de pacotes das distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Actualiza a lista de pacotes disponíveis (recomenda-se executá-lo antes de outros comandos `apt`):

```bash
sudo apt update
```

- Pesquisa pacotes correspondentes ao critério de pesquisa:

```bash
apt search criterio_de_pesquisa
```

- Exibe as informações de um pacote:

```bash
apt show nome_do_pacote
```

- Instala um pacote ou actualiza-o para a versão mais recente:

```bash
sudo apt install nome_do_pacote
```

- Remove um pacote (Para remover os ficheiros de configuração deve-se usar a opção `purge` em vez de `remove`):

```bash
sudo apt remove nome_do_pacote
```

- Actualiza os pacotes instalados para as versões mais recentes:

```bash
sudo apt upgrade
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Tiago Carrondo](mailto:2323546+tcarrondo@users.noreply.github.com) | apt: add pt_PT translation (#7159) | 2021-11-02T00:48:45 | [f8675074402b](https://github.com/tldr-pages/tldr/commit/f8675074402b90d0726f01a5853b4dad383acd20)

