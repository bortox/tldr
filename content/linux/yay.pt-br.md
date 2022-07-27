---
author: ['Ricardo H H Kojo']
date: 1634126506
title: "yay, TLDR Pages"
description: "yay, Yet Another Yogurt: Um utilitário de Arch Linux para compilar e instalar pacotes do AUR (Arch User Repository)."
categories: "linux"
---
> Veja também `pacman`.

> Mais informações: <https://github.com/Jguer/yay>.

- Busca interativamente e instala pacotes dos repositórios e AUR:

```bash
yay nome_do_pacote|termo_de_busca
```

- Sincroniza e atualiza todos os pacotes dos repositórios e AUR:

```bash
yay
```

- Sincroniza e atualiza apenas pacotes AUR:

```bash
yay -Sua
```

- Instala um novo pacote de repositório e AUR:

```bash
yay -S nome_do_pacote
```

- Remove um pacote instalado, suas dependências e arquivos de configuração:

```bash
yay -Rns nome_do_pacote
```

- Procura no banco de dados de pacotes por uma palavra-chave dos repositórios e AUR:

```bash
yay -Ss palavra_chave
```

- Remove pacotes órfãos (instalado como dependência mas não utilizado por qualquer pacote):

```bash
yay -Yc
```

- Mostra estatísticas dos pacotes instalados e condição do sistema:

```bash
yay -Ps
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Ricardo H H Kojo](mailto:ricardo.kojo.dev@gmail.com) | yay: add pt_BR translation Signed-off-by: Ricardo H H Kojo <ricardo.kojo.dev@gmail.com> | 2021-10-13T14:01:46 | [b3e4eea89ca7](https://github.com/tldr-pages/tldr/commit/b3e4eea89ca7f5db7cc29977693797aa9daa6f2f)

