---
author: ['Rafael Julio']
date: 1634750179
title: "dumpsys"
description: "dumpsys, Fornece informações sobre os serviços do sistema Android."
categories: "android"
---
> Este comando só pode ser usado através de `adb shell`.

> Mais informações: <https://developer.android.com/studio/command-line/dumpsys>.

- Gera um diagnóstico de todos os serviços do sistema:

```bash
dumpsys
```

- Gera um diagnóstico de um serviço do sistema específico:

```bash
dumpsys servico
```

- Lista todos os serviços que o `dumpsys` pode obter informações:

```bash
dumpsys -l
```

- Lista argumentos específicos-de-um-serviço para um serviço:

```bash
dumpsys servico -h
```

- Omite um serviço em específico do diagnóstico:

```bash
dumpsys --skip servico
```

- Específica um periodo de _timeout_ (por padrão é 10s):

```bash
dumpsys -t segundos
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | dalvikvm, dumpsys, getprop, input: add pt_BR translation (#7063) | 2021-10-20T19:16:19 | [c3b2c27dd9b9](https://github.com/tldr-pages/tldr/commit/c3b2c27dd9b964b85b4f1074a62a6e725ee0f70a)

