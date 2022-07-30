---
author: ['Axel Navarro', 'Gustavo Cavalieri Fernandes']
date: 1641649180
title: "a2query"
description: "a2query, Exibe configurações de execução do Apache em sistemas operacionais baseados no Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apache2/a2query.html>.

- Lista módulos ativos do Apache:

```bash
sudo a2query -m
```

- Verifica se um módulo específico está instalado:

```bash
sudo a2query -m nome_do_modulo
```

- Lista host virtuais ativos:

```bash
sudo a2query -s
```

- Exibe o módulo de multi processamento atualmente ativo:

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
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | a2dissite, a2enconf, a2enmod, a2ensite, a2query: add pt_BR translation (#7052) | 2021-10-27T20:48:56 | [7e54b2b1658b](https://github.com/tldr-pages/tldr/commit/7e54b2b1658b731c7948f9dfb7246bbd37a80980)

