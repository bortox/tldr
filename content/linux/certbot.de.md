---
author: ['Michael Schwarz', 'marchersimon']
date: 1619262596
title: "certbot"
description: "certbot, The Let's Encrypt Agent zum automatischen Erhalten und Erneuern von TLS-Zertifikaten."
categories: "linux"
---
> Nachfolger von `letsencrypt`.

> Weitere Informationen: <https://certbot.eff.org/docs/using.html>.

- Beziehe ein neues Zertifikat über die webroot-Autorisierung, aber ohne dieses automatisch zu installieren:

```bash
sudo certbot certonly --webroot --webroot-path pfad/zu/webroot --domain subdomain.beispiel.de
```

- Beziehe ein neues Zertifikat über die nginx-Autorisierung und automatische Installation des neuen Zertifikats:

```bash
sudo certbot --nginx --domain subdomain.beispiel.de
```

- Beziehe ein neues Zertifikat über die apache-Autorisierung und automatische Installation des neuen Zertifikats:

```bash
sudo certbot --apache --domain subdomain.beispiel.de
```

- Erneuere alle Let's Encrypt Zertifikate die in 30 Tagen oder weniger auslaufen (nicht vergessen alle Server, die diese nutzen, neu zu starten):

```bash
sudo certbot renew
```

- Simuliere die Zertifikatserneuerung, ohne diese zu speichern:

```bash
sudo certbot --webroot --webroot-path pfad/zu/webroot --domain subdomain.beispiel.de --dry-run
```

- Beziehe eine Test-Zertifikat:

```bash
sudo certbot --webroot --webroot-path pfad/zu/webroot --domain subdomain.beispiel.de --test-cert
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Michael Schwarz](mailto:089michael@gmail.com) | certbot, code, phpbu: add German translation (#4865) | 2020-10-26T13:19:59 | [ec8f27608d37](https://github.com/tldr-pages/tldr/commit/ec8f27608d37ce42a368f35708eb56bbdbd9d496)

