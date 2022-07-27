---
author: ['Andreia Bohner']
date: 1658135504
title: "apachectl, TLDR Pages"
description: "apachectl, Interface de controle do Servidor HTTP Apache para macOS."
categories: "osx"
---
> Mais informações: <https://www.unix.com/man-page/osx/8/apachectl/>.

- Iniciar o job launchd `org.apache.httpd`:

```bash
apachectl start
```

- Parar o job launchd:

```bash
apachectl stop
```

- Parar, e então iniciar o job launchd:

```bash
apachectl restart
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | apachectl: add pt_BR translation | 2022-07-18T11:11:44 | [c4ce1b716ec9](https://github.com/tldr-pages/tldr/commit/c4ce1b716ec9121f8633c69642e28f68ee7cf567)

