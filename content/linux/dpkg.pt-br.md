---
author: ['marchersimon', 'Marco Bonelli', 'Axel Navarro', 'Gustavo Cavalieri Fernandes']
date: 1641649180
title: "dpkg, TLDR Pages"
description: "dpkg, Gerenciador de pacotes Debian."
categories: "linux"
---
> Alguns subcomandos como `dpkg deb` tem sua própia documentação de uso.

> Mais informações: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Instalar um pacote:

```bash
dpkg -i arquivo.deb
```

- Remover um pacote:

```bash
dpkg -r nome_do_pacote
```

- Exibir os pacotes correspondentes ao critério de busca:

```bash
dpkg -l criterio_de_busca
```

- Exibe o conteúdo do pacote:

```bash
dpkg -L nome_do_pacote
```

- Exibir o conteúdo do arquivo de um pacote:

```bash
dpkg -c arquivo.deb
```

- Apresentar o pacote proprietário de um determinado arquivo:

```bash
dpkg -S nome_do_arquivo
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | *: mention subcommands in pt_BR translation (#6798) | 2021-10-05T20:03:43 | [ed5274772bd2](https://github.com/tldr-pages/tldr/commit/ed5274772bd2b09eb465abfd4e132f47048783a2)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

