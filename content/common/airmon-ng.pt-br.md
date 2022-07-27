---
author: ['kp']
date: 1620241489
title: "airmon-ng, TLDR Pages"
description: "airmon-ng, Ativa modo de monitoramento em dispositivos de rede sem-fio."
categories: "common"
---
> Mais informações: <https://www.aircrack-ng.org/doku.php?id=airmon-ng>.

- Lista os dispositivos sem-fio e seus respectivos estados:

```bash
sudo airmon-ng
```

- Liga o modo de monitoramento para um dispositivo específico:

```bash
sudo airmon-ng start wlan0
```

- Encerra processos problemáticos que usam dispositivos sem-fio:

```bash
sudo airmon-ng check kill
```

- Desativa o modo de monitoramento para um dispositivo específico:

```bash
sudo airmon-ng stop wlan0mon
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[kp](mailto:77463574+pedrokpp@users.noreply.github.com) | airmon-ng: add pt_BR translation (#5885) | 2021-05-05T21:04:49 | [f6ecd4e00787](https://github.com/tldr-pages/tldr/commit/f6ecd4e007870340261a28cfef3c48feabdf2fe8)

