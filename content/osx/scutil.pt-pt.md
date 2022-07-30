---
author: ['Rúben Silva', 'meowmeowcat']
date: 1636919159
title: "scutil"
description: "scutil, Gere parametros da configuração do sistema."
categories: "osx"
---
> Necessita de permissões de root para modificar configurações.

> Mais informações: <https://ss64.com/osx/scutil.html>.

- Mostra as configurações de DNS:

```bash
scutil --dns
```

- Mostra as configurações de proxy:

```bash
scutil --proxy
```

- Obtêm o nome do computador:

```bash
scutil --get ComputerName
```

- Altera o nome do computador:

```bash
sudo scutil --set ComputerName nome_computador
```

- Obtêm o nome de rede do computador:

```bash
scutil --get HostName
```

- Altera o nome de rede do computador:

```bash
scutil --set HostName nome_rede_computador
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Rúben Silva](mailto:rubensilva945@gmail.com) | scutil, screencapture, systemsetup, ..: add pt_PT translation (#7088) | 2021-11-04T20:33:02 | [835c489a199f](https://github.com/tldr-pages/tldr/commit/835c489a199f47ee2018b55dafa537df727623fe)

