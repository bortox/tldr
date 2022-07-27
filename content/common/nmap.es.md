---
author: ['Gonzalo Contreras Aso', 'bl-ue']
date: 1619121996
title: "nmap, TLDR Pages"
description: "nmap, Herramienta de exploración de redes y escáner de seguridad / puertos."
categories: "common"
---
> Algunas características solo funcionan si ejecutamos Nmap con privilegios.

> Más información: <https://nmap.org>.

- Comprueba si una dirección IP está activa, e intenta averiguar el sistema operativo del servidor correspondiente:

```bash
nmap -O ip_o_hostname
```

- Intenta determinar si los hosts están activos y cuáles son sus nombres:

```bash
nmap -sn ip_o_hostname opcional_otra_direccion
```

- Como el anterior, pero también ejecuta un escaneo de 1000 puertos TCP por defecto, si el host está activo:

```bash
nmap ip_o_hostname opcional_otra_direccion
```

- Detecta también scripts, servicios, sistema operativo y traceroute:

```bash
nmap -A direccion_o_direcciones
```

- Asume una buena conexión y acelera la ejecución:

```bash
nmap -T4 direccion_o_direcciones
```

- Escanea una lista específica de puertos (para todos los puertos `1-65535` usar `-p-`):

```bash
nmap -p puerto1,puerto2,…,puertoN direccion_o_direcciones
```

- Realiza un escaneo TCP y UDP (usar `-sU` para solo UDP, `-sZ` para SCTP, `-sO` para IP):

```bash
nmap -sSU direccion_o_direcciones
```

- Realiza un escaneo total de puertos, servicios, detección de versiones con todos los scripts NSE por defecto contra un host para determinar debilidades e información:

```bash
nmap -sC -sV direccion_o_direcciones
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | nmap: put command flags in example descriptions in backticks (#5812) | 2021-04-22T22:06:36 | [43901df7ecde](https://github.com/tldr-pages/tldr/commit/43901df7ecde69084a69fc82df6c77a314ab53b9)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | mkdir, touch, nmap: add Spanish translations (#5491) | 2021-03-23T19:19:37 | [5607caaea147](https://github.com/tldr-pages/tldr/commit/5607caaea1477cb5f793e320d755b0ddd5dfb2c1)

