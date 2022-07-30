---
author: ['Mario Gordon']
date: 1635888102
title: "ufw"
description: "ufw, Cortafuegos sin complicaciones (_Uncomplicated Firewall_)."
categories: "linux"
---
> Interfaz de usuario de iptables para facilitar la configuración de un firewall.

> Más información: <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- Activa ufw:

```bash
ufw enable
```

- Desactiva ufw:

```bash
ufw disable
```

- Muestra reglas del ufw, junto con sus números:

```bash
ufw status numbered
```

- Permite el tráfico entrante en el puerto 5432 en este host con un comentario que identifique el servicio:

```bash
ufw allow 5432 comment "servicio"
```

- Permite sólo el tráfico TCP desde 192.168.0.4 a cualquier dirección de este host, en el puerto 22:

```bash
ufw allow proto tcp from 192.168.0.4 to any port 22
```

- Deniega tráfico en el puerto 80 en este host:

```bash
ufw deny 80
```

- Deniega todo el tráfico al puerto 22:

```bash
ufw deny proto udp from any to any port 22
```

- Elimina una regla concreta. El número de la regla puede obtenerse del comando `ufw status numbered`:

```bash
ufw delete número_de_regla
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Mario Gordon](mailto:80539604+maegop@users.noreply.github.com) | ufw: add Spanish translation (#7313) | 2021-11-02T22:21:42 | [7fb59ee67295](https://github.com/tldr-pages/tldr/commit/7fb59ee672958ec22c1470c30ed8f9a736c85346)

