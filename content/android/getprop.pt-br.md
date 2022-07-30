---
author: ['Rafael Julio']
date: 1634750179
title: "getprop"
description: "getprop, Obtém informações sobre propriedades do sistema Android (system props)."
categories: "android"
---
> Mais informações: <https://manned.org/getprop>.

- Mostra todas as propriedades do sistema:

```bash
getprop
```

- Mostra o valor de uma propriedade específica:

```bash
getprop prop
```

- Mostra o nível de API:

```bash
getprop ro.build.version.sdk
```

- Mostra a versão do Android:

```bash
getprop ro.build.version.release
```

- Mostra o modelo do dispositivo:

```bash
getprop ro.vendor.product.model
```

- Mostra o status de desbloqueio OEM:

```bash
getprop ro.oem_unlock_supported
```

- Mostra o endereço MAC da placa de Wi-Fi do dispositivo:

```bash
getprop ro.boot.wifimacaddr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | dalvikvm, dumpsys, getprop, input: add pt_BR translation (#7063) | 2021-10-20T19:16:19 | [c3b2c27dd9b9](https://github.com/tldr-pages/tldr/commit/c3b2c27dd9b964b85b4f1074a62a6e725ee0f70a)

