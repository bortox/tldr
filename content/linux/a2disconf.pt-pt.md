---
author: ['Tiago Carrondo']
date: 1636401507
title: "a2disconf, TLDR Pages"
description: "a2disconf, Desactiva um ficheiro de configuração do Apache em distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apache2/a2disconf.8.en.html>.

- Desactiva um ficheiro de configuração:

```bash
sudo a2disconf ficheiro_de_configuração
```

- Desactiva um ficheiro de configuração, sem mostrar as mensagens informativas:

```bash
sudo a2disconf --quiet ficheiro_de_configuração
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Tiago Carrondo](mailto:2323546+tcarrondo@users.noreply.github.com) | a2disconf, a2enconf: add pt_PT translation (#7175) | 2021-11-08T20:58:27 | [d2412ea5070c](https://github.com/tldr-pages/tldr/commit/d2412ea5070c23d4a89ca3f1e2ddc94d98194625)

