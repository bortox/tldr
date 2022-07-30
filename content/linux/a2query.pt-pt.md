---
author: ['Tiago Carrondo', 'Axel Navarro']
date: 1641649180
title: "a2query"
description: "a2query, Mostra configurações runtime do Apache em distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apache2/a2query.html>.

- Lista módulos Apache activados:

```bash
sudo a2query -m
```

- Verifica de um módulo específico está instalado:

```bash
sudo a2query -m module_name
```

- Lista os hosts virtuais activados:

```bash
sudo a2query -s
```

- Mostra o módulo de multi processamento actualmente activado:

```bash
sudo a2query -M
```

- Mostra a versão do Apache:

```bash
sudo a2query -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Tiago Carrondo](mailto:2323546+tcarrondo@users.noreply.github.com) | a2disiste, a2ensite, a2query: add pt_PT translation (#7424) | 2021-12-01T11:25:46 | [db8b2353d591](https://github.com/tldr-pages/tldr/commit/db8b2353d5912e7de5aa7135ba68c2e2b41b1fd6)

