---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "uname, TLDR Pages"
description: "uname, Apresenta detalhes sobre o hardware e sistema operacional do computador."
categories: "common"
---
> Nota: Para maiores detalhes sobre o sistema operacional, utilize o comando `lsb_release`.

> Mais informações: <https://www.gnu.org/software/coreutils/uname>.

- Exibir informações relacionadas ao hardware: arquitetura e tipo de processador:

```bash
uname -mp
```

- Exibir informações relacionadas ao software: sistema operacional, número da release e versão:

```bash
uname -srv
```

- Exibir o nome de rede do computador:

```bash
uname -n
```

- Exibir todas as informações disponíveis do sistema (hardware, software, nome de rede):

```bash
uname -a
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | uname: add more information link (#5633) | 2021-03-30T16:01:18 | [4f4592712cd8](https://github.com/tldr-pages/tldr/commit/4f4592712cd8655a7994d9d8d230c468b7bc8a38)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

