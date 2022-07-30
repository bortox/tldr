---
author: ['Ilya Pantsyr']
date: 1650439019
title: "dog"
description: "dog, Утиліта пошуку DNS."
categories: "common"
---
> Вона має кольоровий вихід, підтримує протоколи DNS-over-TLS і DNS-over-HTTPS та може видавати JSON.

> Більше інформації: <https://dns.lookup.dog>.

- Шукає IP-адреси пов'язані з іменем хоста (A records):

```bash
dog example.com
```

- Запитує тип записів MX, пов’язаних із заданим доменним ім’ям:

```bash
dog example.com MX
```

- Вкажіть конкретний DNS-сервер для запиту (наприклад, Cloudflare):

```bash
dog example.com MX @1.1.1.1
```

- Запит через TCP, а не UDP:

```bash
dog example.com MX @1.1.1.1 --tcp
```

- Запитує тип записів MX, пов’язаних із заданим доменним ім’ям через TCP, використовуючи явні аргументи:

```bash
dog --query example.com --type MX --nameserver 1.1.1.1 --tcp
```

- Шукає IP-адреси, пов’язані з іменем хоста (записи A), за допомогою DNS через HTTPS (DoH):

```bash
dog example.com --https @https://cloudflare-dns.com/dns-query
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | dog, dokku: add Ukrainian translation (#8036) | 2022-04-20T09:16:59 | [87781641f6db](https://github.com/tldr-pages/tldr/commit/87781641f6db3a24be43f38f158f1ed92aa1b26d)

