---
author: ['André Almeida']
date: 1603127093
title: "bpftrace, TLDR Pages"
description: "bpftrace, Linguagem de análise de alto nível para eBPF Linux."
categories: "linux"
---
> Mais informações: <https://github.com/iovisor/bpftrace>.

- Verifique a versão do bpftrace:

```bash
bpftrace -V
```

- Lista todos os probes:

```bash
sudo bpftrace -l
```

- Rode um programa de uma linha (e.g. número de syscalls por programa):

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }'
```

- Rode um programa de um arquivo:

```bash
sudo bpftrace caminho/do/arquivo
```

- Analise um programa por PID:

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }'
```

- Mostre o resultado do programa em eBPF, sem rodar ele:

```bash
sudo bpftrace -d -e 'programa_de_uma_linha'
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[André Almeida](mailto:andrealmeid@collabora.com) | bpftrace: add pt_BR translation (#4735) | 2020-10-19T19:04:53 | [a17c9f34e59b](https://github.com/tldr-pages/tldr/commit/a17c9f34e59bdf93c0b6b3571a14e1ce7278ae8d)

