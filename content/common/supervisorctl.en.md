---
author: ['Waldir Pimenta', 'MarloweW', 'Lucas Gabriel Schneider', 'pxgamer', 'Marco Bonelli']
date: 1612112718
title: "supervisorctl"
description: "supervisorctl, Supervisor is a client/server system that allows its users to control a number of processes on UNIX-like operating systems."
categories: "common"
---
> Supervisorctl is the command-line client piece of the supervisor which provides a shell-like interface.

> More information: <http://supervisord.org>.

- Start/stop/restart a process:

```bash
supervisorctl start|stop|restart process_name
```

- Start/stop/restart all processes in a group:

```bash
supervisorctl start|stop|restart group_name:*
```

- Show last 100 **bytes** of process stderr:

```bash
supervisorctl tail -100 process_name stderr
```

- Keep displaying stdout of a process:

```bash
supervisorctl tail -f process_name stdout
```

- Reload process config file to add/remove processes as necessary:

```bash
supervisorctl update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | supervisorctl: add link to homepage | 2019-05-14T19:58:59 | [ef1ee4298527](https://github.com/tldr-pages/tldr/commit/ef1ee42985275037293f982f8df8bb8a589c22a7)
[MarloweW](mailto:MarloweW@users.noreply.github.com) | supervisord & supervisorctl: add page (#1226) | 2017-01-06T07:52:05 | [8ce649c7b9b0](https://github.com/tldr-pages/tldr/commit/8ce649c7b9b08c8a13d47b32e87343c4a8b6636d)

