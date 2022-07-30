---
author: ['Rafael Julio']
date: 1634750076
title: "settings"
description: "settings, Exibe, edita e apaga configurações do sistema Android."
categories: "android"
---
> Mais informações: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Exibe a lista de configurações no namespace `global`:

```bash
settings list global
```

- Obtém o valor de uma configuração específica:

```bash
settings get global airplane_mode_on
```

- Edita o valor de uma configuração:

```bash
settings put system screen_brightness 42
```

- Apaga uma configuração:

```bash
settings delete secure screensaver_enabled
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | logcat, pm, settings, wm: add pt_BR translation (#7064) | 2021-10-20T19:14:36 | [fb1e0c85582d](https://github.com/tldr-pages/tldr/commit/fb1e0c85582da98e8c7816cd3a9c27f769ed19ba)

