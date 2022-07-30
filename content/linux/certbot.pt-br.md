---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "certbot"
description: "certbot, O agente da Let's Encrypt para obtenção e renovação de certificados TLS automaticamente."
categories: "linux"
---
> Sucessor do `letsencrypt`.

> Mais informações: <https://certbot.eff.org/docs/using.html>.

- Obter um novo certificado via autorização webroot, porém sem instalá-lo automaticamente:

```bash
sudo certbot certonly --webroot --webroot-path caminho_para_webroot --domain subdominio.dominio.com
```

- Obter um novo certificado via autorização nginx e instalá-lo automaticamente:

```bash
sudo certbot --nginx --domain subdominio.dominio.com
```

- Obter um novo certificado via autorização apache e instalá-lo automaticamente:

```bash
sudo certbot --apache --domain subdominio.dominio.com
```

- Renovar todos os certificados que expirarão em 30 dias ou menos (não esqueça de reiniciar todos os servidores que usam os certificados):

```bash
sudo certbot renew
```

- Simular a obtenção de um novo certificado, porém sem salvá-lo no disco rígido:

```bash
sudo certbot --webroot --webroot-path caminho_para_webroot --domain subdominio.dominio.com --dry-run
```

- Obter um certificado não confiável para testes:

```bash
sudo certbot --webroot --webroot-path caminho_para_webroot --domain subdominio.dominio.com --test-cert
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

