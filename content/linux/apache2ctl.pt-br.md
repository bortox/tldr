---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "apache2ctl, TLDR Pages"
description: "apache2ctl, Interface de controle do servidor web HTTP Apache."
categories: "linux"
---
> Este comando está disponível nas distribuições baseadas em Debian, para as baseadas em RHEL veja `httpd`.

> Mais informações: <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Iniciar o Apache. Caso ele já esteja em execução, uma mensagem será apresentada:

```bash
sudo apache2ctl start
```

- Encerrar o Apache:

```bash
sudo apache2ctl stop
```

- Reiniciar o Apache:

```bash
sudo apache2ctl restart
```

- Verificar se o arquivo de configuração está correto sintaticamente:

```bash
sudo apache2ctl -t
```

- Listar os módulos carregados:

```bash
sudo apache2ctl -M
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | apache2ctl: add more information link (#5541) | 2021-03-31T13:12:50 | [5ca9ff460d5c](https://github.com/tldr-pages/tldr/commit/5ca9ff460d5c7f50b062c02e532021e54efe9f25)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

