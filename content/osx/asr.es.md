---
author: ['Alberto García Sola', 'Kyle']
date: 1629747204
title: "asr"
description: "asr, Restaura (copia) una imagen de disco en un volumen."
categories: "osx"
---
> El nombre del comando significa Restauración de Software de Apple.

> Más información: <https://www.unix.com/man-page/osx/8/asr/>.

- Restaura una imagen de disco en un volumen:

```bash
sudo asr restore --source nombre_de_imagen.dmg --target ruta/al/volumen
```

- Borra el volumen deseado antes de restaurar:

```bash
sudo asr restore --source nombre_de_imagen.dmg --target ruta/al/volumen --erase
```

- Omite la verificación después de restaurar:

```bash
sudo asr restore --source nombre_de_imagen.dmg --target ruta/al/volumen --noverify
```

- Clona volúmenes sin el uso de una imagen de disco intermedia:

```bash
sudo asr restore --source ruta/al/volumen --target ruta/al/volumen_clonado
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Alberto García Sola](mailto:44441820+dawalberto@users.noreply.github.com) | afinfo, afplay, airport, apachectl, archey, as, asr: add Spanish translation (#4596) | 2020-10-12T23:00:27 | [6ffb27546e7a](https://github.com/tldr-pages/tldr/commit/6ffb27546e7a1ae721ea732aa42b9adc44453da2)

