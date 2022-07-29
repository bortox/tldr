---
author: ['Luis']
date: 1659013746
title: "acpi, TLDR Pages"
description: "acpi, Exibe status da bateria ou informações térmicas."
categories: "linux"
---
> Mais informação: <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Exibe informações sobre a bateria:

```bash
acpi
```

- Exibe informações térmicas:

```bash
acpi -t
```

- Exibe informações sobre dispositivo de resfriamento:

```bash
acpi -c
```

- Exibe informações térmicas em Fahrenheit:

```bash
acpi -tf
```

- Exibe todas as informações:

```bash
acpi -V
```

- Extrai informações de `/proc` em vez de `/sys`:

```bash
acpi -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis](mailto:CasperBraske@users.noreply.github.com) | acpi: add pt_BR translation (#8260) | 2022-07-28T15:09:06 | [7fdfdc5d59ea](https://github.com/tldr-pages/tldr/commit/7fdfdc5d59eab03e1b8b62d5f171e7c2a28eea92)

