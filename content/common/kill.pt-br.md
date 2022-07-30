---
author: ['bl-ue', 'Carlos Vieira', 'lincc']
date: 1632006650
title: "kill"
description: "kill, Envia um sinal para um processo, geralmente para finalizar o processo."
categories: "common"
---
> Todos os sinais exceto pelo SIGKILL e SIGSTOP podem ser interceptados pelo processo para finalizar de forma limpa.

> Mais informações: <https://manned.org/kill>.

- Finaliza um programa usando o sinal default SIGTERM (terminate):

```bash
kill id_do_processo
```

- Lista todos os nomes dos sinais disponíveis (para serem usados sem o prefixo `SIG`):

```bash
kill -l
```

- Finaliza um processo em background:

```bash
kill %id_do_processo
```

- Finaliza um programa usando o sinal SIGHUP. Muitos daemons vão recarregar ao invés de finalizar:

```bash
kill -1|HUP id_do_processo
```

- Finaliza um programa usando o sinal SIGINT (interrupt). Isto é tipicamente iniciado pelo usuário ao pressionar `Ctrl + C`:

```bash
kill -2|INT id_do_processo
```

- Envia sinal para o sistema operacional para finalizar imediatamente o programa (quem não tem chance de capturar o sinal):

```bash
kill -9|KILL id_do_processo
```

- Envia sinal para o sistema operacional para pausar o programa até um sinal SIGCONT ("continue") seja recebido:

```bash
kill -17|STOP id_do_processo
```

- Envia um sinal `SIGUSR1` para todos os processos de um dado GID (group id):

```bash
kill -SIGUSR1 -id_do_grupo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | jobs, jstack, kill, killall: add more information link (#6545) | 2021-09-19T01:10:50 | [0e7393b78f1d](https://github.com/tldr-pages/tldr/commit/0e7393b78f1db36b5dfb377b3062c6b551a69e58)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Portuguese (Brazil) pages: fix (valid) tldr-lint errors (#5369) | 2021-03-08T20:42:47 | [443568f165ec](https://github.com/tldr-pages/tldr/commit/443568f165eccbfa2521da66158f07e4e9d3bd7a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | kill: translating commands arguments pt_BR | 2020-10-28T19:19:36 | [5c79b628b820](https://github.com/tldr-pages/tldr/commit/5c79b628b82001cbbcfebb40fafab40281d25011)
[Carlos Vieira](mailto:edu.carlos.vieira@gmail.com) | kill: add pt_BR translation | 2020-10-28T19:19:36 | [b9142a56f631](https://github.com/tldr-pages/tldr/commit/b9142a56f6313f58ee7b1ef2ba14cacca6832c7f)

